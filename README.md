# Daniel Palacios

**Ph.D. Candidate, Quantitative & Computational Biosciences** — Baylor College of Medicine
NSF Graduate Research Fellow (2024) · NLM Fellow (2023) · Dean's Award of Excellence (2024)

I build LLM-powered clinical pipelines, agentic AI systems, and predictive models for healthcare. My work spans postpartum mental health prediction, pediatric disease phenotyping, PHI de-identification, and computational modeling for NASA space biology missions — deployed at scale using AWS and Palantir Foundry across 50,000+ patient records.

---

### Research & Projects

**Postpartum Depression Prediction** — Agentic AutoML system on AWS Bedrock for EPDS score prediction across 6,600+ patients using multimodal EHR data. Under review at *PLOS Digital Health*. [[preprint]](https://doi.org/10.1101/2025.11.14.25340265)

**Pediatric Diabetes Cohorts (T1D & T2D)** — Clinician-validated cohorts (~4,000 T1D; ~2,500 T2D patients) with 80+ longitudinal variables extracted via Palantir Foundry, including LLM-driven SDOH extraction from social work notes. 3 accepted abstracts; NIDDK grant funded.
[[T1D repo]](https://github.com/DanPalBCM/Palantir_T1D_Scripts) · [[T2D repo]](https://github.com/DanPalBCM/Palantir_T2D_Scripts)

**Trofinetide (Daybue) Treatment Response** — Multi-stage LLM pipeline (summarizer → extractor → validator → enrollment checker) for longitudinal phenotype monitoring in 115 Rett syndrome patients. 65% agreement with nurse annotations; first automated analysis of this $500K medication.
[[repo]](https://github.com/DanPalBCM/Palantir_Trofinetide)

**PHI De-identification Benchmarking** — Evaluated 7 commercial LLMs and 3 custom hybrid pipelines on ~36,000 PHI entities from TCH clinical notes. Best approach (LLM scrubber + regex safety net + precision auditor) achieved 98.6% recall. Publication in preparation.
[[repo]](https://github.com/DanPalBCM/Palantir_PHI-Scrubber)

**Hyperthyroidism Analysis** — PySpark pipeline for identifying Free T4 normalization timelines and computing hyperthyroidism duration from longitudinal lab data.
[[repo]](https://github.com/DanPalBCM/HyperThyroidism)

**Immunodeficiency Phenotyping** — LLM-based phenotype extraction pipeline with two-stage prompting (extractor + validator) and fuzzy-match recall evaluation against clinician annotations.
[[repo]](https://github.com/DanPalBCM/Palantir_Immunodeficiency)

**Prenatal HPO Extraction** — Benchmarked 6 phenotype extraction tools (PhenoGPT, Doc2HPO, ClinPhen, FastHPOCR, GPT, Claude RAG) on prenatal clinical notes. Manuscript in preparation.
[[repo]](https://github.com/DanPalBCM/Palantir_PreNatal)

**Epilepsy & Sleep Disorders** — Seizure phenotype extraction and event discovery pipeline combining LLM analysis with OMOP/flowsheet structured data mining for pediatric epilepsy-sleep disorder research.
[[repo]](https://github.com/DanPalBCM/Palantir_Sleeping_Disorders)

**PENTALPHA** — LSTM-based patient trajectory prediction from OMOP records (2.8M patients, 284M events). Benchmarked against LLM baselines. Publication in preparation.

**AI Synapse** — Ontology-augmented generation system for pediatric oncology clinical decision support. Best model: GPT-5.4 at 94.1% accuracy on clinician-curated questions.

**NASA AMMPER** — Agent-based simulation of microbial cell damage under space radiation, validated against Biosentinel mission data. Published in *Scientific Reports*. [[paper]](https://doi.org/10.1038/s41598-026-36813-7)

---

### Publications

D. Palacios et al. "ClinPreAI: An Agentic AI System for Early Postpartum Depression Risk Prediction from Multimodal EHR Data." *PLOS Digital Health* (under review). [[preprint]](https://doi.org/10.1101/2025.11.14.25340265)

D. Palacios, Hill, T.R. "Taxonomical modeling and classification in space hardware failure reporting." *Scientific Reports* (2026). [[paper]](https://doi.org/10.1038/s41598-026-36813-7)

Hosur, P., D. Palacios. "Proximity-induced equilibrium supercurrent and perfect superconducting diode effect due to band asymmetry." *Physical Review B* (2023). [[paper]](https://doi.org/10.1103/PhysRevB.108.094513)

+ 2 additional manuscripts under review, 3 in preparation

---

### Technical Stack

**ML & AI:** LLM fine-tuning (QLoRA/PEFT), prompt engineering, RAG, agentic AI, AutoML, deep learning (CNNs, LSTMs, Transformers)
**Languages:** Python (6+ yrs), R (3+ yrs), SQL (3+ yrs)
**Platforms:** Palantir Foundry (Pipeline Builder, AIP Agents), AWS (SageMaker, Bedrock), Docker, Git
**Python ecosystem:** PyTorch, PySpark, scikit-learn, LangChain, LangGraph, Hugging Face, spaCy, Optuna

---

### Open-Source Software

[**AMMPER**](https://github.com/DanPalBCM) — Agent-based simulation of microbial populations under space radiation (NASA)
[**OverlapPlots**](https://github.com/DanPalBCM) — R package for neurological gene expression analysis (BioConductor)

---

### Contact

daniel.palacios@bcm.edu · [LinkedIn](https://www.linkedin.com/in/daniel-palacios-506734224/) · [ORCID](https://orcid.org/)
