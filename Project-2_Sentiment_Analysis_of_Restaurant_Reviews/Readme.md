# 🍽️ Sentiment Analysis of Restaurant Reviews

## 📌 Project Overview
This project performs **Sentiment Analysis on Restaurant Reviews** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The model predicts whether a customer review expresses a **Positive** or **Negative** sentiment.

---

## 🎯 Problem Statement
Customer reviews contain valuable insights about restaurant services and food quality. Manually analyzing large volumes of reviews is difficult and time-consuming. This project aims to automatically classify restaurant reviews into positive and negative sentiments.

---

## 💼 Business Objective
- Analyze customer feedback efficiently.
- Understand customer satisfaction levels.
- Identify areas needing improvement.
- Support data-driven business decisions.
- Improve overall customer experience.

---

## 📊 Dataset Information

| Attribute | Description |
|------------|-------------|
| Dataset | Restaurant Reviews Dataset |
| Total Records | 1000 |
| Feature | Review |
| Target Variable | Liked (0 = Negative, 1 = Positive) |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🧹 Data Preprocessing

The following preprocessing techniques were applied:

- Removed special characters and punctuation
- Converted text to lowercase
- Tokenization
- Stopword removal
- Stemming using Porter Stemmer
- Bag of Words (BoW) feature extraction
- Train-Test Split

---

## 📈 Exploratory Data Analysis (EDA)

### Key Insights

- Reviews contain both positive and negative customer opinions.
- Text cleaning improves model performance.
- Bag of Words effectively converts text into numerical features.
- Customer sentiment can be accurately predicted using NLP techniques.

---

## 🤖 Model Building

### Algorithm Used
- Multinomial Naive Bayes

### Workflow
1. Data Cleaning
2. Text Preprocessing
3. Feature Extraction using CountVectorizer
4. Train-Test Split
5. Model Training
6. Prediction
7. Performance Evaluation

---

## 📊 Evaluation Metrics

| Metric | Score |
|----------|----------|
| Accuracy | 78.5% |
| Precision | 0.76 |
| Recall | 0.79 |

---

## ✅ Results

The **Multinomial Naive Bayes** model successfully classified restaurant reviews into positive and negative sentiments.

### Best Performance
- Accuracy: **78.5%**
- Model: **Multinomial Naive Bayes**
- Optimal Alpha Value: **0.2**

---

## 📂 Project Structure

```text
Sentiment-Analysis-Restaurant-Reviews/
│
├── Dataset/
│   └── Restaurant_Reviews.tsv
│
├── Notebook/
│   └── Sentiment Analysis of Restaurant Reviews.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 Installation & Usage

```bash
# Clone repository
git clone https://github.com/your-username/Sentiment-Analysis-Restaurant-Reviews.git

# Navigate to project folder
cd Sentiment-Analysis-Restaurant-Reviews

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

## 🔮 Future Improvements

- TF-IDF Feature Engineering
- Logistic Regression Implementation
- Random Forest Comparison
- Hyperparameter Optimization
- Deep Learning Models (LSTM, BERT)
- Flask/FastAPI Deployment
- Real-Time Sentiment Prediction API

---

## 📸 Output

### Sample Prediction

| Review | Predicted Sentiment |
|----------|--------------------|
| The food was amazing and service was excellent. | Positive 😊 |
| Worst restaurant experience ever. | Negative 😞 |

---

## 👨‍💻 Author

### Ramu Patro

Aspiring Data Scientist | Machine Learning Enthusiast | Data Analyst

[![GitHub](https://img.shields.io/badge/GitHub-ramupathro07-black?style=for-the-badge&logo=github)](https://github.com/ramupathro07)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ramu%20Patro-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/patro-ramu-0b2587231)

⭐ If you found this project useful, consider giving it a star.

💡 Open to Data Science, Machine Learning, and Data Analyst opportunities.
