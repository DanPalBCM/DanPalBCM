# Daniel Palacios

**Ph.D. Candidate, Quantitative & Computational Biosciences** — Baylor College of Medicine  
NSF Graduate Research Fellow (2024) · NLM Fellow (2023) · Dean's Award of Excellence (2024) · Outstanding TA (2025)

I build LLM-powered clinical pipelines, agentic AI systems, and predictive models for healthcare. My work spans postpartum mental health prediction, pediatric disease phenotyping, PHI de-identification, and computational modeling for NASA space biology missions — deployed at scale using AWS and Palantir Foundry across 2.8M+ patient records.

---

### Research & Projects

**ClinPreAI — Postpartum Depression Prediction** — Multi-agent AutoML system with five modules that ingests multimodal EHR data (27 structured variables + unstructured notes), autonomously designs ML workflows, and iteratively refines predictive models. Applied to EPDS score prediction across 4,100+ patients; outperformed traditional AutoML (F1: 0.68 vs. 0.64) and AWS Canvas (F1: 0.54). Under review at *PLOS Digital Health*. [[preprint]](https://doi.org/10.1101/2025.11.14.25340265)

**Pediatric Diabetes Cohorts (T1D & T2D)** — Clinician-validated cohorts (~4,000 T1D; ~2,500 T2D patients) with 80+ longitudinal variables extracted via Palantir Foundry, including LLM-driven SDOH extraction from social work notes. Custom algorithm resolves cross-contamination in PheKB phenotyping. Predictive models for hypoglycemia and DKA events. 3 accepted abstracts; NIDDK grant funded.  
[[T1D repo]](https://github.com/DanPalBCM/Palantir_T1D_Scripts) · [[T2D repo]](https://github.com/DanPalBCM/Palantir_T2D_Scripts)

**Trofinetide (Daybue) Treatment Response** — Multi-stage LLM pipeline (summarizer → extractor → validator → enrollment checker) for longitudinal phenotype monitoring in 115 Rett syndrome patients. 65% agreement with nurse annotations; first automated analysis of this $500K medication.  
[[repo]](https://github.com/DanPalBCM/Palantir_Trofinetide)

**AI Synapse — Pediatric Oncology Clinical Decision Support** — Ontology-augmented generation system in Palantir Foundry using AIP Agent, embedding clinical notes and practice guidelines for treatment matching. Benchmarked multiple foundation models on 68 clinician-curated questions; best model: GPT-5.4 at 94.1% accuracy. Error analysis revealed systematic failure patterns across difficulty levels.

**PHI De-identification Benchmarking** — Evaluated 7 commercial LLMs and 3 custom hybrid pipelines on ~36,000 PHI entities from TCH clinical notes. Best approach (LLM scrubber + regex safety net + precision auditor) achieved 98.6% recall. Publication in preparation.  
[[repo]](https://github.com/DanPalBCM/Palantir_PHI-Scrubber)

**PENTALPHA — Patient Trajectory Prediction** — LSTM model for predicting clinical trajectories from complete OMOP records (2.8M patients, 284M events). Expanded feature space to include medications, measurements, and labs with curated FDA OTC filtering pipeline. Benchmarked against LLM baselines (LLaMA, Qwen, Mistral). Publication in preparation.  
[[repo]](https://github.com/LiuzLab/pentalpha)

**MedSDoH — Social Determinants of Health Extraction** — Rule-based system for SDOH extraction from multi-site EHRs based on the OHNLP framework. Under review at *JAMIA*.  
[[repo]](https://github.com/OHNLP/MedSDoH) · [[fork]](https://github.com/DanPalBCM/MedSDoH)

**Prenatal HPO Extraction** — Benchmarked 6 phenotype extraction tools (PhenoGPT, Doc2HPO, ClinPhen, FastHPOCR, GPT, Claude RAG) on prenatal clinical notes. Manuscript in preparation.  
[[repo]](https://github.com/DanPalBCM/Palantir_PreNatal)

**Epilepsy & Sleep Disorders** — Seizure phenotype extraction and event discovery pipeline combining LLM analysis with OMOP/flowsheet structured data mining for pediatric epilepsy-sleep disorder research.  
[[repo]](https://github.com/DanPalBCM/Palantir_Sleeping_Disorders)

**Immunodeficiency Phenotyping** — LLM-based phenotype extraction pipeline with two-stage prompting (extractor + validator) and fuzzy-match recall evaluation against clinician annotations.  
[[repo]](https://github.com/DanPalBCM/Palantir_Immunodeficiency)

**Hyperthyroidism Analysis** — PySpark pipeline for identifying Free T4 normalization timelines and computing hyperthyroidism duration from longitudinal lab data.  
[[repo]](https://github.com/DanPalBCM/HyperThyroidism)

**NASA AMMPER** — Agent-based simulation of microbial cell damage under space radiation, validated against Biosentinel mission data. Published in *Scientific Reports*.  
[[paper]](https://doi.org/10.1038/s41598-026-36813-7) · [[repo]](https://github.com/nasa/AMMPER)

---

### Publications

**D. Palacios** et al. "ClinPreAI: An Agentic AI System for Early Postpartum Depression Risk Prediction from Multimodal EHR Data." *PLOS Digital Health* (under review). [[preprint]](https://doi.org/10.1101/2025.11.14.25340265)

**D. Palacios**, Hill, T.R. "Taxonomical modeling and classification in space hardware failure reporting." *Scientific Reports* (2026). [[paper]](https://doi.org/10.1038/s41598-026-36813-7)

Goulding, A.N., **D. Palacios** et al. "Factors associated with postpartum depression symptoms following antepartum hospitalization." *SMFM Pregnancy* (under review).

Ahn, J., Fu, S., **D. Palacios** et al. "MedSDoH: A Rule-Based System for Social Determinants of Health Extraction from Multi-site EHRs based on the OHNLP Framework." *JAMIA* (under review).

Hosur, P., **D. Palacios**. "Proximity-induced equilibrium supercurrent and perfect superconducting diode effect due to band asymmetry." *Physical Review B* (2023). [[paper]](https://doi.org/10.1103/PhysRevB.108.094513)

+ 3 additional manuscripts in preparation

---

### Technical Stack

**ML & AI:** LLM fine-tuning (QLoRA/PEFT), prompt engineering, RAG, agentic AI, multi-agent system design, AutoML, deep learning (CNNs, LSTMs, Transformers)  
**Languages:** Python (6+ yrs), R (3+ yrs), SQL (3+ yrs), MATLAB (2+ yrs)  
**Platforms:** Palantir Foundry (Pipeline Builder, AIP Agents, OAG), AWS (SageMaker, Bedrock), Docker, Git, Power BI  
**Python ecosystem:** PyTorch, PySpark, scikit-learn, LangChain, LangGraph, Hugging Face, spaCy, Optuna, Pandas, NumPy, SciPy

---

### Open-Source Software

[**AMMPER**](https://github.com/nasa/AMMPER) — Agent-based simulation of microbial populations under space radiation (NASA Biosentinel & LEIA missions)  
[**PENTALPHA**](https://github.com/LiuzLab/pentalpha) — LSTM-based patient trajectory prediction from OMOP records  
[**MedSDoH**](https://github.com/OHNLP/MedSDoH) — Rule-based SDOH extraction from multi-site EHRs (OHNLP) · [[fork]](https://github.com/DanPalBCM/MedSDoH)  
[**TCH Mentor Matching**](https://github.com/LiuzLab/tch-mentormatching) — RAG system for matching mentees with Texas Children's Hospital mentors  
[**OverlapPlots**](https://github.com/LiuzLab/OverlapPlots) — R package for neurological gene expression analysis (BioConductor)

---

### Awards & Fellowships

GSBS Outstanding TA in Quantitative & Computational Biosciences (2025) · Dean's Award of Excellence, BCM (2024) · NSF Graduate Research Fellowship (2024) · NLM Fellowship T15LM007093-32 (2023) · ASM Future Leaders Mentoring Fellowship (2023) · Lathisms Scholarship (2023) · IMSD NIH-NIGMS Grant (2022) · Magna Cum Laude, University of Houston (2022)

---

### Contact

daniel.palacios@bcm.edu · [LinkedIn](https://www.linkedin.com/in/daniel-palacios-506734224/) · [ORCID](https://orcid.org/0000-0001-9608-3311) · [GitHub](https://github.com/DanPalBCM)
