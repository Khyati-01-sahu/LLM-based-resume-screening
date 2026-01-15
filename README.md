# LLM-Based Resume Screening & Candidate Matching System

This project builds an AI-powered hiring intelligence system that automatically ranks resumes against job descriptions using NLP embeddings and LLM-generated explanations. The system helps recruiters shortlist candidates objectively, faster, and more accurately.

---

## 📌 Business Problem
Recruiters manually screen thousands of resumes, leading to bias, inconsistency, and slow hiring. This project automates candidate-job matching using AI to:
- Rank resumes based on relevance
- Generate natural-language explanations
- Support data-driven hiring decisions

---

## 📊 Data
The system uses:
- Resume text (PDF / text files)
- Job Description text  

Each resume is converted into text and compared against the JD.

---

## ⚙️ Approach
1. Text extraction from resumes  
2. Text preprocessing  
3. Sentence embedding generation using transformer models  
4. Cosine similarity between resume and JD  
5. Candidate ranking based on similarity score  
6. LLM-generated explanation for candidate-job fit  

---

## 📈 Output
- Ranked list of candidates  
- Similarity score for each candidate  
- Natural-language explanation of why a candidate fits a job  

---

## 🛠 Tech Stack
- Python  
- Sentence-Transformers  
- OpenAI / LLM API  
- Scikit-learn  
- Pandas  

---

## 🚀 How to Run
```bash
pip install pandas scikit-learn sentence-transformers openai
python resume_matcher.py
