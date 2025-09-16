# ❓ Question Answering with Transformers

This project is part of my Elevvo Internship (NLP Track).  
The goal of this task is to build a Question Answering system using transformer-based models from Hugging Face.

---

## 📌 Project Steps

Step 1: Install and Import Libraries  
Installed Hugging Face Transformers, Datasets, and Evaluate libraries.

Step 2: Load Dataset (SQuAD v1.1)  
Loaded the Stanford Question Answering Dataset, which contains passages, questions, and answers.

Step 3: Load Pre-trained Model and Tokenizer  
Used the pre-trained DistilBERT model fine-tuned on SQuAD.  
The tokenizer converts text into tokens, and the model extracts answer spans.

Step 4: Create QA Pipeline  
Created a Hugging Face pipeline for question answering.  
The model predicts answers based on the given context and question.

Step 5: Evaluate the Model  
Evaluated the model on 200 validation samples using Exact Match (EM) and F1 Score.

Step 6 (Bonus): Try Another Model  
Tested another model (RoBERTa fine-tuned on SQuAD) to compare performance.

---

## 📊 Results

- DistilBERT (on 200 samples):
  - Exact Match (EM): ~78%  
  - F1 Score: ~84%

- RoBERTa (sample test):
  - Correctly answered a custom question:  
    *"Who was the first president of the United States?" → "George Washington"*

---

## 🛠️ Tools & Libraries Used

- Python  
- Hugging Face Transformers  
- Hugging Face Datasets  
- Evaluate  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/question-answering-transformers.git
   pip install transformers datasets evaluate
   2. Install dependencies:
python -m spacy download en_core_web_sm
3. Run the notebook in Google Colab.
🌟 Internship Info

This project is part of my Elevvo Internship (Natural Language Processing Track).
It covers transformer-based NLP, span extraction, evaluation with EM/F1, and model comparison.
