# 🧠 NLP Yelp Sentiment Analysis Project

This project focuses on sentiment analysis using the **Yelp Review Full** dataset from Hugging Face.  
The objective was to train and evaluate a model capable of outperforming a provided fine-tuned BERT baseline.

---

## 📊 Dataset

- **Name:** Yelp Review Full
- **Source:** Hugging Face
- **Task:** Multi-class sentiment classification (1 to 5 stars)
- **Domain:** Restaurant reviews

---

## 🎯 Objective

The goal of this project was to:

- Train a sentiment classification model on Yelp reviews
- Compare performance against a fine-tuned BERT baseline
- Analyze model performance using standard evaluation metrics
- Document and justify all methodological choices

---

## 🛠 Methodology

The following steps were performed:

1. Data exploration and preprocessing  
2. Text cleaning and tokenization  
3. Model training  
4. Evaluation on the test set  
5. Performance comparison  

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Confusion Matrix
- Precision
- Recall
- F1-Score
- Training Time

Results are available in:
- `figures/` → Confusion matrix visualization
- `docs/` → Classification report and training time
- `Final report/` → Complete project report (PDF)

---

## 📂 Repository Structure
.
├── notebooks/
│ └── train_eval.ipynb # Training and evaluation notebook
│
├── figures/
│ └── confusion_matrix.png # Visualization results
│
├── docs/
│ ├── classification_report.txt
│ ├── training_time.txt
│ └── report.md
│
├── Final report/
│ └── final_report_NLP.pdf
│
└── README.md
---

## 🚀 Installation & Usage

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/nlp-yelp-sentiment-project.git
cd nlp-yelp-sentiment-project
### 2️⃣ Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate
### 3️⃣ Install dependencies
pip install -r requirements.txt
### 4️⃣ Run the notebook
notebooks/train_eval.ipynb
## 📌 Baseline Comparison

The project compares its results against:

- A fine-tuned BERT model trained on the same Yelp dataset

Performance comparison focuses on:

- F1-score
- Precision / Recall balance
- Training efficiency

---

## 🧪 Technical Stack

- Python  
- PyTorch  
- Transformers (Hugging Face)  
- Scikit-learn  
- NumPy / Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📎 Deliverables

✔ Training Time  
✔ Confusion Matrix  
✔ Precision / Recall / F1-score  
✔ Full Project Report  
✔ Model Evaluation Documentation  

---

## 📚 Key Learnings

- Practical experience with transformer fine-tuning  
- Handling large NLP datasets  
- Multi-class sentiment classification challenges  
- Model evaluation and performance analysis  
- Structured experimentation workflow  

---

## 👤 Author

**Anas Khalil**  
MSc Computer Science & Data Science  
Specialization: NLP • Machine Learning • AI  

---

## 📌 Academic Context

This project was completed as part of a Natural Language Processing module, where the objective was to build and evaluate a sentiment classification system capable of outperforming a baseline transformer model.

---

## ⭐ Future Improvements

- Hyperparameter optimization with automated search  
- Data augmentation  
- Ensemble methods  
- Deployment as an API  
- Model compression for production use  

---

## 🔥 After Updating

Run:

```bash
git add README.md
git commit -m "Update README with baseline and project details"
git push
