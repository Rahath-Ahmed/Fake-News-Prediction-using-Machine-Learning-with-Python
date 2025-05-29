# 📰 Fake News Detection using Machine Learning

This project builds a machine learning model to detect fake news using text preprocessing techniques and a logistic regression classifier. The goal is to distinguish between real and fake news articles based on their text content.

---

## 📁 Dataset

- **Source**: [Fake News Dataset – Google Drive](https://drive.google.com/file/d/1Ol2Y21VlfNyzlS7nAdku0e4uaOglEnn8/view?usp=drive_link)
- **Features**:
  - `title` – Headline of the news article  
  - `author` – Author's name  
  - `text` – Full content of the article  
  - `label` – Target (1 = Fake, 0 = Real)

---

## 🧰 Technologies Used

- Python  
- Pandas & NumPy  
- scikit-learn  
- NLTK (Natural Language Toolkit)  
- TfidfVectorizer  
- Logistic Regression

---

## 🚀 Workflow

1. Import dependencies and load the dataset  
2. Preprocess the text (stopwords removal, stemming, etc.)  
3. Vectorize text using TF-IDF  
4. Split data into training and testing sets  
5. Train a Logistic Regression model  
6. Evaluate model performance  
7. Make a prediction system

---

## ✅ Results

- **Model**: Logistic Regression  
- **Preprocessing**: Stopword removal, stemming, TF-IDF vectorization  
- **Performance**: Accuracy depends on data split but performs well as a baseline model

---

## ▶️ How to Use

1. Clone the repo or download the notebook.  
2. Make sure the dataset is linked correctly.  
3. Run the notebook in Jupyter or Google Colab.

---

## 📌 Future Improvements

- Try more advanced models like Naive Bayes, Random Forest, or LSTM  
- Combine the ```author``` and ```title``` columns with ```text``` column into a single input field before preprocessing to improve model accuracy

---

## 🙏 Acknowledgments

- NLTK & Scikit-learn communities
