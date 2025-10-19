## Prompt Design Research — Core Input Categories

The following framework defines the key informational areas that any intelligent prompt system for websites or apps should gather **before** the build process begins.  
Each section represents a data stream that feeds context into the master prompt, ensuring the AI understands the purpose, scope, and tone of the project.

A good prompt is not about asking “What should I build?” — it’s about **feeding the AI everything it needs to stop guessing**.

---

### **1. Project Overview**
Defines the overall purpose and boundaries of the build.
- **Purpose:** Clarify what’s being built — website, app, landing page, or hybrid system.  
- **Example questions:**
  - What is the core function of this project?  
  - Is it informational, transactional, or interactive?  
  - What’s the main goal — conversions, awareness, engagement?

---

### **2. Branding**
Establishes the visual identity and personality that the AI should follow.
- **Purpose:** Enforce brand consistency through tone, color, and design cues.  
- **Example questions:**
  - What are your logo, brand colors, and fonts?  
  - How would you describe your brand personality (playful, minimal, luxury)?  
  - Should the AI reflect existing brand guidelines?

---

### **3. Goals**
Sets measurable objectives for the final output.
- **Purpose:** Help the AI prioritize structure, tone, and features that meet clear outcomes.  
- **Example questions:**
  - What does “success” look like for this project?  
  - Are you measuring clicks, sales, leads, or engagement?  
  - Are there short-term and long-term targets?

---

### **4. Target Audience**
Defines the user profiles and their expectations.
- **Purpose:** Shape copy, layout, and functionality for specific users.  
- **Example questions:**
  - Who is the primary user? (Age, interests, technical ability)  
  - Are there accessibility or cultural factors to consider?  
  - Should the tone be formal or conversational?

---

### **5. Content & Voice**
Controls how the system generates text and messaging.
- **Purpose:** Aligns writing tone and structure with brand goals.  
- **Example questions:**
  - Should the tone be friendly, direct, or professional?  
  - Any key slogans, phrases, or voice traits to include or avoid?  
  - Should the AI emulate an existing writing style?

---

### **6. Layout & Structure**
Determines how the AI organizes the build visually.
- **Purpose:** Prevents layout randomness by defining the navigation and visual hierarchy early.  
- **Example questions:**
  - How many main pages or sections?  
  - What’s the preferred navigation type (top bar, sidebar, single-scroll)?  
  - Any example layouts you like?

---

### **7. Features & Integrations**
Defines functionality and external connections.
- **Purpose:** Allow the AI to plan technical structure and include required systems.  
- **Example questions:**
  - Does it need e-commerce, booking, or forms?  
  - Should it integrate with CRM, Google Maps, or APIs?  
  - Any special interactions or animations needed?

---

### **8. Technical Requirements**
Sets limits and preferences for the generated code.
- **Purpose:** Prevents the AI from building outside of practical constraints.  
- **Example questions:**
  - Should it use React, Vue, or plain HTML/CSS?  
  - Are there hosting, framework, or performance constraints?  
  - Should it be optimized for mobile-first or specific browsers?

---

### **9. Accessibility**
Ensures inclusive design principles are baked in from the start.
- **Purpose:** Make the build compliant and user-friendly for all audiences.  
- **Example questions:**
  - Should it support screen readers?  
  - Are there color-contrast or keyboard navigation needs?  
  - Does accessibility affect layout or font choices?

---

### **10. SEO (Search Engine Optimization)**
Improves how the AI builds discoverable, structured content.
- **Purpose:** Help the AI understand visibility goals and metadata structure.  
- **Example questions:**
  - What are the target keywords or search intent?  
  - Should meta titles and descriptions be generated?  
  - Is there existing SEO copy to reuse?

---

### **11. Analytics**
Defines data tracking and reporting needs.
- **Purpose:** Add visibility tools that measure performance and engagement.  
- **Example questions:**
  - Should Google Analytics or similar be embedded?  
  - What KPIs should be tracked?  
  - Do you need event tracking or custom dashboards?

---

### **12. Compliance**
Handles legal and regulatory requirements.
- **Purpose:** Prevents accidental violations in content or data handling.  
- **Example questions:**
  - Does the site need GDPR or CCPA compliance?  
  - Should cookie consent or privacy policies be auto-generated?  
  - Any industry-specific requirements (finance, medical, etc.)?

---

### **13. Budget**
Defines resource constraints for realistic build complexity.
- **Purpose:** Guides scope decisions and limits over-engineering.  
- **Example questions:**
  - What is the total project budget?  
  - Should the AI prioritize low-cost hosting or automation?  
  - Are there budget caps for additional features?

---

### **14. Timeline**
Sets temporal goals for delivery.
- **Purpose:** Keeps AI output realistic for deadlines and staging.  
- **Example questions:**
  - What is the target launch date?  
  - Are there multiple release phases or milestones?  
  - Should the prompt simulate an agile workflow?

---

### **15. Special Requests**
Captures anything not covered elsewhere.
- **Purpose:** Allow room for creativity, unique requirements, or niche goals.  
- **Example questions:**
  - Any custom design ideas, integrations, or edge-case functionality?  
  - Should the AI prioritize innovation or stability?  
  - Anything you explicitly don’t want included?

---

## Summary
This research identifies **15 core information categories** that together form a complete context map for AI-driven website and app generation.  
When integrated into the prompt creator, these categories become the backbone of a structured intake process — ensuring that **every AI output is intentional, brand-aligned, and usable in production**.

The next stage of research will map these categories into a **prompt-to-schema translation layer**, defining how user inputs become structured JSON for worker orchestration.
