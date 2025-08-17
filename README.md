# AI-Powered Resume Screening and Ranking System 📄🤖  

An intelligent system that leverages **Natural Language Processing (NLP)** and **Machine Learning (ML)** to automate and optimize the resume screening process.  
The system analyzes resumes and job descriptions, matches candidates to job requirements, and ranks them based on relevance, thereby reducing human bias, improving efficiency, and enhancing the recruitment experience.  

---

## 🔑 Key Features
- **Automated Resume Parsing** – Extracts structured data (skills, education, experience) from resumes (PDF, DOCX, etc.).  
- **Job Description Analysis** – Identifies required skills, qualifications, and experience.  
- **Candidate Matching & Ranking** – Compares resumes with job requirements using AI/ML models.  
- **Bias Reduction** – Integrates fairness-aware algorithms to minimize unconscious biases.  
- **User-Friendly Interface** – Interactive dashboard (Streamlit-based) for uploading resumes and job descriptions.  
- **Analytics & Reporting** – Provides insights on candidate selection and hiring trends.  

---

## ⚙️ Tech Stack

**Languages & Libraries:**  
- Python (primary language)  
- NLP Libraries – NLTK, SpaCy, Hugging Face Transformers  
- ML Models – SVM, Naive Bayes, XGBoost, KNN, BERT  

**Frameworks & Tools:**  
- Streamlit (Frontend UI)  
- Scikit-learn, TensorFlow/PyTorch (Model training)  
- Pandas, NumPy (Data preprocessing)  

**Storage:**  
- PostgreSQL / MySQL for structured candidate data  
- MongoDB / Vector DB (Pinecone, Weaviate) for embeddings  

---

## 📊 System Workflow
1. Upload **Job Description** & **Resumes**  
2. Preprocessing using **TF-IDF / Transformer embeddings**  
3. Similarity computation with **Cosine Similarity / ML ranking models**  
4. Candidate ranking and display on dashboard  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+  
- Install dependencies:  
```bash
pip install -r requirements.txt
