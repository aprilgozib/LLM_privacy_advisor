# LLM Privacy Advisor
**Large Language Model-Driven Privacy Compliance Recommender for ML Systems under the EU AI Act**

A toolkit that analyzes machine learning workflows, detects privacy risks (e.g., PII exposure, memorization risk), and generates **actionable privacy recommendations grounded in regulatory texts** using **LLM + Retrieval-Augmented Generation (RAG)**.

---

## Motivation
Regulatory frameworks such as the **EU AI Act** and **GDPR** require AI systems to be:
- Privacy-preserving  
- Risk-aware  
- Transparent and auditable  

However, **developers currently have no practical tools** to check *whether* and *how* their ML pipelines comply.  
This project bridges that gap with a **regulation-aware recommendation system.**

---

## Key Features
- **Regulation-aware reasoning:** grounded in EU AI Act & GDPR
- **RAG-based:** LLM responses cite retrieved regulatory text
- **Actionable mitigation steps:** not just classification
- **Differential Privacy (DP) integration:** optional privacy hardening
- **Auditable output:** risk report + citations

---

## System Architecture


**Flow Overview:**
1. Input ML workflow + dataset schema  
2. Retrieve relevant legal text from the Regulatory KB  
3. LLM generates grounded privacy risk explanation  
4. Recommender suggests **concrete mitigation steps**  
5. (Optional) Apply DP strategies  

---
