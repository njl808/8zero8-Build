## Research Methodology — Using Perplexity Labs Effectively

This section documents the process and workflow used inside **Perplexity Labs** to conduct structured, repeatable research for the 8zero8-build Prompt Creator.  
The aim is to ensure that every finding, category, and schema is traceable, verifiable, and grounded in real implementations — not speculative AI output.

---

### **1. Query Design**

Each Perplexity query begins with a **clear research intent**, usually framed as:
- *“Identify how AI website builders structure user input prompts.”*  
- *“Compare information architecture patterns between Bolt.new, Open-Lovable-DIY, and similar tools.”*  
- *“Find examples of JSON schemas used for modular prompt design.”*  

Queries are written in **plain, instructional English**, avoiding vague terms like “best” or “cool” that trigger summarization fluff.  
This ensures Perplexity retrieves **implementation data**, not surface commentary.

---

### **2. Layered Prompt Refinement**

Perplexity is used iteratively — not as a one-off query.  
Each research cycle follows this structure:

1. **Seed Query:** broad search to discover available documentation or examples.  
2. **Pattern Extraction:** identify recurring themes, structures, or categories.  
3. **Focused Drill-Down:** narrow queries to gather detail on each pattern.  
4. **Cross-Validation:** re-run findings with slightly altered wording to confirm consistency.  
5. **Data Consolidation:** summarise results into structured notes (tables or JSON).  

This layering approach ensures factual overlap across multiple sources — a safeguard against single-source bias or hallucination.

---

### **3. Categorisation & Schema Drafting**

Collected insights are grouped into the 15 **Prompt Input Categories** (see research section above).  
For each category, Perplexity’s results are distilled into:
- The **purpose** of that data field,  
- Common **example questions**,  
- Any **dependencies** or relationships with other categories, and  
- Potential **schema keys** for future JSON structure.

This forms the first draft of the **Prompt Schema Dictionary** — a document that defines what the AI needs to ask, store, and reference during generation.

---

### **4. Validation Against Real Builders**

Findings are compared with actual AI builders and code repositories:
- Open-Lovable-DIY (GitHub)  
- Bolt.new / Vercel templates  
- Open source React-based site generators  
- Headless CMS prompt tools and schema repos  

If Perplexity’s extracted logic appears in live systems, it’s marked as **validated**.  
Unverified structures are tagged for further testing in the 8zero8-build sandbox.

---

### **5. Documentation & Versioning**

All validated results are recorded as Markdown or JSON files under `/docs/research/` inside the repository.  
Each research session is versioned with:
- Query summary  
- Key takeaways  
- Validation status  
- Next steps  

This allows transparent tracking of what was discovered, what’s confirmed, and what’s pending review.

---

### **6. Integration Pipeline**

When a finding passes validation, it’s imported into the **Prompt Engine roadmap** as one of the following:
- **Prompt Module:** reusable question/answer pattern  
- **Schema Definition:** structured field with constraints  
- **Worker Instruction:** guidance text for a specific AI worker (Writer, Layout, etc.)  

This pipeline ensures a continuous handoff from research → design → implementation.

---

### **7. Model Cross-Testing**

To prevent model bias, final prompt drafts are run through multiple free-tier AI providers (OpenRouter, Groq, Kimi).  
The output is evaluated for:
- Consistency of tone and structure  
- Adherence to schema logic  
- Token efficiency  

Any model that deviates too far from expected output helps identify weaknesses in the prompt’s clarity — prompting another refinement round.

---

### **Summary**

Perplexity Labs acts as the **research backbone** of 8zero8-build, not a creative generator.  
Its role is to collect, verify, and structure the data that defines how AI builders should think — ensuring future builds by GPT-5, Kimi, or any other model remain consistent, scalable, and technically sound.

This methodology creates a feedback loop where **research informs architecture**, and architecture in turn informs **prompt logic** — forming the foundation of a true AI-driven builder ecosystem.
