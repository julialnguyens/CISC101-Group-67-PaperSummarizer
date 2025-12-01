# Research Paper Summarizer

## What this project does
This project takes a research paper and makes summaries of it.  
It creates different kinds of summaries (expert, layperson, glossary, etc.) and checks for missing or short sections.

## Main parts of the system
- **Module 1 — Intake & Setup**  
  Handles the inputs (paper text, sections, audience, settings). Makes sure everything is labeled and valid.

- **Module 2 — Section Loop**  
  Goes through each section of the paper one by one and makes summaries. Keeps the same order as the paper.

- **Module 3 — Guardrails**  
  Stops the system from making things up. Flags missing or very short sections.

- **Module 4 — Rendering & Refinement**  
  Puts all the summaries together, formats them, and adds the glossary and warnings.

- **Module 5 — Citation Extractor**  
  Pulls out all the citations from the paper. Warns if citations are missing.

- **Module 6 — Key Contribution Highlighter**  
  Finds the top 3–5 contributions of the paper and explains them in expert and layperson terms.

## Rules
- Don’t invent sections or citations.  
- Use the paper’s own terminology.  
- Respect word limits.  
- Summaries must follow the paper’s section order.  
- Always give warnings if something is missing or too short.

## Outputs
- Paper Summary (overall abstract)  
- Section-by-Section Summary Table  
- Expert Summary  
- Lay Summary  
- Mini-Glossary  
- Checks & Warning Messages  
- Citation List  
- Key Contributions
