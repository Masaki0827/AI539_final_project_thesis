# Report Writing Roadmap: AI Interview Coach

This roadmap tracks the writing progress of the final report in `main.tex`, synchronized with the development stages of the AI539 final project.

## Section 1: Introduction & Abstract
- [x] **Abstract:** Summarize problem, methodology (RLAIF/DPO), and general results.
- [x] **Introduction:** Define the technical interview gap and motivation for a specialized coach.
- [x] **Problem Statement:** Explain why base LLMs struggle with technical coaching.

## Section 2: Related Work
- [x] **RLHF/RLAIF:** Review existing alignment techniques.
- [x] **Direct Preference Optimization:** Discuss the DPO advantage for this project.
- [x] **AI in Education:** Contextualize the coach within existing STEM feedback tools.

## Section 3: Methodology (Synchronized with Project Progress)
- [x] **Dataset Construction:** Describe the 4,853 source questions (Completed in Project).
- [x] **Student Simulation:** Explain the first-year CS Master persona and failure modes (Completed in Project).
- [x] **RLAIF Pipeline:** Detail the Judge (Qwen3.5-9B) and preference labeling process (Completed in Project).
- [x] **Optimization Strategy:** Describe QLoRA, SFT, and DPO training setups (In Progress in Project).

## Section 4: Experimental Results (DEPENDENT ON PROJECT COMPLETION)
- [x] **Evaluation Metric:** Define the 1-20 rubric and 5-dimension scoring system.
- [x] **Baseline Performance:** Report scores for the base Qwen2.5-3B model (Completed in Project).
- [ ] **DPO Improvement:** Analyze final model performance and win rates (Pending Project Step 8-10).
- [ ] **Qualitative Analysis:** Showcase specific examples of "Exceptional" feedback vs. baseline.
- [ ] **Ablation/Bias Analysis:** Discuss the impact of different feedback styles and bias controls.

## Section 5: Discussion & Conclusion
- [ ] **Limitations:** Reflect on model size constraints and simulated data limits.
- [ ] **Future Work:** Outline multi-modal and live-platform integration goals.
- [x] **Bibliography:** (In Progress) Finalize BibTeX entries for all cited papers.

## Final Review Checklist
- [ ] Cross-check figures/tables with final evaluation data.
- [ ] Verify page length (4-8 pages requirement).
- [ ] Perform final grammar and technical accuracy pass.
