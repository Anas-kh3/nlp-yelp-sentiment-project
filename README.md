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
