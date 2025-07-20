# 💬 Sentiment Analysis of Dell Product Reviews using RoBERTa-Large

This project explores **sentiment analysis** using Dell product reviews collected from social platforms. The core goal was to **predict user sentiment (Positive, Negative, Neutral)** using **state-of-the-art NLP models**.

## 🎯 Objective
To develop a highly accurate text classification model that can interpret user sentiments on Dell product reviews.

---

## 📌 Key Highlights

- ✅ **Model Used**: `RoBERTa-Large` (Pretrained transformer model)
- ✅ **Achieved Accuracy**: **99.1%** on test data
- ✅ Compared performance of traditional models (Logistic Regression) vs transformer-based models
- ✅ Fully preprocessed text using custom NLP pipeline

---

## 🛠 Tools & Technologies

- Python  
- Transformers (HuggingFace)  
- RoBERTa-Large  
- scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## 📊 Methodology

1. **Data Cleaning**: Removing HTML tags, symbols, stopwords, and special characters
2. **Exploratory Data Analysis**: Class balance, word clouds, and token patterns
3. **Model Training**:
   - Fine-tuned `roberta-large` using Hugging Face Transformers
   - Used GPU for faster training
4. **Evaluation**:
   - Achieved **99.1% accuracy**
   - Precision, Recall, F1-score, and Confusion Matrix

---

## 🧠 Model Comparison

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 84.5%    |
| RoBERTa-Large       | **99.1%**    |

---

## 📂 Files

- `notebook472fb6474e.ipynb`: Jupyter Notebook with full workflow
- `dell_reviews.csv`: *(Dataset not shared for privacy)*
- `model_roberta.pkl`: (Not included here, but mentioned for future deployment)

---

## 🚀 Future Improvements

- Deploy model as a sentiment analysis API (FastAPI/Flask)
- Visual dashboard using Streamlit
- Add real-time review analysis using web scraping or Twitter API

---

## 📌 Author

**Zeeshan Haider**  
  
- Email: haideriam251@gmail.com

