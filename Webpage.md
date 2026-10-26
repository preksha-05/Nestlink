# NestLink – Vertical Webpage (PPT-style) Codex Instructions

## Objective
Generate a **single-page vertical scrolling website** that functions like a presentation (PPT-style). The layout should follow a **section-by-section storytelling flow**, based on a Figma design (PNG to be provided) and the structure below.

The output should be clean, modern, and minimal, with strong visual hierarchy and smooth scrolling between sections.

---

## Input अपेक्षित (from user)
- Figma export (PNG image of full design)
- Content text (optional, can be refined/expanded by agent)

---

## Technical Requirements

- Use **HTML + CSS + minimal JavaScript (if needed)**
- Responsive design (optimized for laptop + tablet; mobile optional but preferred)
- Smooth vertical scrolling
- Section-based layout (full-screen or near full-screen panels)
- Use flex/grid for layout
- Fonts: Clean sans-serif (e.g., Inter, Poppins)
- Animations: Subtle (fade-in, slide-up on scroll)
- No heavy frameworks unless necessary

---

## Page Structure (Top → Bottom)

### 1. Introduction / Cover Section
- Title: **NestLink**
- Subtitle: Ambient Elderly Monitoring System
- Name
- University
- Full-screen hero section
- Optional: background gradient or image from Figma

---

### 2. Start of the Process
- Brief introduction of how the project began
- Problem discovery context
- Use visuals if available (from PNG)

---

### 3. Main Area → Transition
- Explain initial focus area
- Show how understanding evolved over time
- Visual storytelling preferred (timeline/flow if possible)

---

### 4. Interview Findings & Process
- Key research insights
- Interview highlights
- Process followed (user research, synthesis, etc.)
- Use cards or bullet sections

---

### 5. Background & Context
- Broader problem space
- Why this problem matters
- Include contextual explanation (aging, independence, care gap)

---

### 6. Final Problem Context
- Narrowed-down problem after research
- Clear explanation of refined focus

---

### 7. Problem Statement (7 HMWs)
- Display **7 “How Might We” statements**
- Use grid or stacked cards

---

### 8. Stakeholder Mapping
- Show different stakeholders:
  - Elderly users
  - Family members
  - Caregivers
- Visual diagram if possible (or structured layout)

---

### 9. Solution Ideation
- Show exploration phase
- Multiple ideas considered
- Can include sketches (from PNG)
- Highlight why final direction was chosen

---

### 10. Final Solution / Product
- Introduce **NestLink**
- High-level concept explanation
- Strong visual emphasis

---

### 11. Forms & Product System
- Show system components:
  - Smart Cup
  - Smart Door Knob
  - Sound Artifact
  - Central Receiver
- Layout: grid or modular cards

---

### 12. Features & Product Explanation
Break down features:

- Passive monitoring
- No wearables
- Ambient feedback (light-based)
- Priority alerts system

Each feature should have:
- Title
- Short description
- Optional icon/visual

---

### 13. Future Scope
- Possible extensions:
  - Mobile app
  - AI insights
  - Emergency integration
  - More sensor objects

---

## Design Guidelines

- Follow Figma PNG closely for layout, spacing, and visuals
- Maintain consistent spacing and typography scale
- Use whitespace effectively
- Sections should feel like slides
- Add subtle transitions between sections

---

## Behavior & UX

- Smooth scroll between sections
- Optional: scroll snapping
- Fade-in animations on section entry
- Keep interactions minimal and elegant

---

## Output Format अपेक्षित

Codex should generate:

1. `index.html`
2. `styles.css`
3. (Optional) `script.js`

---

## Notes for Agent

- Treat each section as a **presentation slide**
- Prioritize **visual clarity over text density**
- If PNG includes layout cues, replicate them as closely as possible
- Do not clutter UI
- Maintain a premium, minimal design language

---

## Placeholder Handling

If exact content is missing:
- Use structured placeholders
- Clearly label sections for easy replacement

---

## End Goal

A **scrollable storytelling webpage** that replaces a traditional PPT, clearly presenting the NestLink design process from research → insights → solution.