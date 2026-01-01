# Developing a Foundational Dataset for Urdu Text Summarization

## Overview
Urdu is a widely spoken language with limited high-quality resources for text summarization research. The lack of standardized datasets and clear design guidelines significantly hinders the development and evaluation of summarization models. This project addresses that gap by proposing a **conceptual framework and measurable quality thresholds** for constructing a reliable Urdu text summarization dataset.

Rather than focusing solely on model performance, the research emphasizes **data quality, annotation consistency, and reproducibility**, which are critical for low-resource NLP.

---

## Research Contributions
- Proposes a **systematic framework** for building foundational Urdu summarization datasets  
- Defines **design thresholds** for dataset quality, including:
  - Domain diversity requirements
  - Annotation quality scoring (Likert-scale based)
  - Inter-annotator agreement using **Fleiss’ Kappa (≥ 0.7)**
- Incorporates **Urdu-specific preprocessing**, including Nastaliq normalization and morphological considerations
- Establishes scalable dataset size targets for pilot and full-scale development
- Validates the framework through **extractive summarization techniques**

---

## Linguistic Challenges Addressed
- Rich morphology and inflection  
- Free word order  
- Nastaliq script normalization  
- Perso-Arabic vocabulary influence  

These factors are explicitly accounted for in the dataset design and preprocessing pipeline.

---

## Methodology Summary
- Multi-domain source acquisition (news, academic, literary text)
- Specialized preprocessing tailored to Urdu
- Human annotation with quality scoring
- Reliability validation using ROUGE metrics and inter-annotator agreement
- Extractive summarization used as a practical baseline for evaluation

---

## Repository Contents
This repository includes:
- Research Paper – Full paper describing the framework, thresholds, and methodology  
- Code Implementation – NLP preprocessing and extractive summarization experiments  
- Presentation Slides (PPT) – Project presentation used for academic dissemination  

The paper, code, and presentation are all included to support **reproducibility and transparency**.

---

## Conference Submission
This paper has been **submitted to the International Conference on Communication, Computing and Internet of Things (ICCIIoT)**  
UET Peshawar  
https://www.uetpeshawar.edu.pk/icciiot/

---

## Citation
If you use or build upon this work, please cite it as:

**Saeed et al., *Developing a Foundational Dataset for Urdu Text Summarization***  

(A formal BibTeX entry will be added upon acceptance/publication.)

---

## Authors
Ayesha Saeed  
Ayesha Ehsaan  
Shahzain Zaidi  
Abdullah Adil  

FAST National University of Computer & Emerging Sciences (NUCES), Karachi, Pakistan

---

## Notes
This work is intended as a **foundational contribution** for future Urdu NLP research and can be extended to abstractive summarization and larger-scale datasets.
