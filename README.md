# SMS Spam Classifier

This project is a machine learning-based SMS Spam Classifier that classifies text messages as either **spam** or **ham (not spam)**. The model is built using various text preprocessing techniques and multiple machine learning algorithms, including **Logistic Regression**, **Naive Bayes**, **Random Forest**, and **Decision Tree**.

The project also includes the development of a **Streamlit** app to allow users to input text messages and receive real-time spam classification predictions.

## Demo
Use the **Streamlit** app to classify SMS messages as spam or ham by typing them into the input box.

## Features
- **Label Encoding** and **Porter Stemmer** for text preprocessing and cleaning.
- **TF-IDF** (Term Frequency-Inverse Document Frequency) for feature extraction from the text.
- Classification using **Logistic Regression**, **Naive Bayes**, **Random Forest**, and **Decision Tree** algorithms.
- **Streamlit** web app to classify user-entered SMS messages in real-time.
- Performance metrics include **Accuracy (0.97)** and **Precision (0.98)**.

## Technologies & Tools
- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Word Cloud**
- **Scikit-learn** (Logistic Regression, Naive Bayes, Random Forest, Decision Tree)
- **TF-IDF**, **Porter Stemmer**, **Label Encoding**
- **Streamlit** (for app development)


## 🏁 How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/Teena-Sapra/sms-spam-classifier.git
cd sms-spam-classifier
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app:**
```bash
streamlit run app.py
```

4. **Enter an SMS message in the input box to see if it is classified as spam or ham.**

