# AI Tool Usage Disclosure

## Student Information
- **Student name:** Lais Santos Silva
- **Course:** MAI 600 – Natural Language Processing
- **Module:** Module 3 – Attention & the Transformer Architecture
- **Assignment:** Attention & Architecture Walkthrough
- **Date:** July 26th, 2026

## AI Tools Used
- [x] Claude
- [x] Claude Code
- [ ] ChatGPT
- [ ] GitHub Copilot
- [ ] OpenAI Codex
- [x] Gemini
- [ ] Other:

## How I Used AI
- **Directed the project decisions myself:** I chose the **finance/business operations** domain (to match my professional interest) and the **hybrid track** (manual analysis + a real pretrained model). 
- **Concept explanation:** I asked AI to explain queries, keys, values, attention weights, and multi-head attention in plain language so I could write the reflection in my own words.
- **Drafting the fictional text:** AI helped word the fictional finance variance-report paragraph. It contains no real, private, or proprietary data.
- **Notebook scaffolding:** AI helped structure the notebook (tokenization, the by-hand NumPy attention example, the Hugging Face attention extraction, the heatmaps, and the tables) and added fallbacks so it runs even offline.
- **Diagram layout:** AI suggested the 13-box Transformer flow layout and generated the diagram image.
- **Formatting:** AI helped format this README and disclosure.
- **Debug:** Utilized Gemini embedded in Colab to correct errors. 

## What I Verified Myself
- I ran the notebook in **Google Colab** end-to-end and confirmed the cells execute without errors.
- I checked the **by-hand Q/K/V example** and confirmed that "it" attends most to "report" — the same result the math predicts.
- I inspected the **real attention heatmap** and the "what does *it* look at" ranking to confirm the pronoun-resolution behavior is plausible in the actual model.
- I confirmed the diagram includes **all 13 required components** and that the paragraph is **~120 words** (within the 100–250 range) with no sensitive data.
- I checked the sub-word tokenization output and confirmed accruals and overspend split while reconciled, ledger, and variance stay whole.

## What I Changed or Corrected After Using AI
- I reviewed every table and reworded explanations so they reflect **my own understanding**, not just AI phrasing.
- After running §6 I noticed the all-head average did not differentiate A vs B. I requested a re-run isolating the strongest head, which attended it → report in both sentences (0.752 vs 0.799) — so it continued to show proximity rather than true resolution.
- I cross-checked §6 against the §5b scan (Layer 6, Head 10 = 0.816).
- I reworded the markdown throughout in my own voice.
- I corrected a tokenization claim (reconciled does not split into ##led) to match the real output.
- Wrote reflection and adjusted for tone based on real finding.


## Work Ownership Statement
I confirm that AI was used as a learning and support tool, not as a replacement for my own work. I reviewed and verified the final submission and can explain the concepts, tables, diagram, and notebook in my own words.
