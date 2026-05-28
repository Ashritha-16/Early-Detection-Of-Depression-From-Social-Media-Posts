# 🧠 Early Detection of Depression From Social Media Posts

A Machine Learning and Django-based web application that predicts signs of depression from social media posts using Natural Language Processing (NLP) techniques.

---

# 📌 Project Overview

This project analyzes text data from social media posts and predicts whether the content indicates signs of depression.
The system uses Machine Learning algorithms along with NLP preprocessing techniques to classify user text efficiently.

The application was developed using:

* Python
* Django
* Machine Learning
* Natural Language Processing (NLP)
* HTML, CSS, Bootstrap
* SQLite / MySQL

---

# 🚀 Features

* 🔐 User Registration & Login System
* 👨‍💼 Admin Dashboard
* 🧠 Depression Prediction from User Text
* 📝 NLP Text Preprocessing
* 📊 Machine Learning Classification
* 📈 Dataset Analysis
* 🌐 Interactive Web Interface
* 📱 Responsive Design

---

# 🛠️ Technologies Used

## Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

## Backend

* Python
* Django

## Machine Learning & NLP

* Scikit-learn
* NLTK
* Pandas
* NumPy

## Database

* SQLite
* MySQL

---

# 📂 Project Structure

```bash id="1y6h6x"
EarlyDetectionOfDepressionFromSocialMediaPosts/
│
├── admins/
├── users/
├── static/
├── templates/
├── EarlyDetectionOfDepressionFromSocialMediaPosts/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
│   └── __init__.py
│
├── manage.py
├── requirements.txt
├── nltkdownload.py
├── download_nltk.bat
└── Run Test.bat
```

---

# ⚙️ How the System Works

1. User enters social media text.
2. NLP preprocessing is applied:

   * Tokenization
   * Stopword removal
   * Stemming
3. Features are extracted from text data.
4. Machine Learning models classify the text.
5. The system predicts whether the post indicates depression.

---

# 🤖 Machine Learning Models Used

* Support Vector Machine (SVM)
* Naive Bayes
* Decision Tree

Among these models, **SVM achieved the best performance** for text classification.

---

# ▶️ How to Run the Project

## 1️⃣ Install Dependencies

```bash id="wttmwo"
pip install -r requirements.txt
```

## 2️⃣ Download NLTK Data

```bash id="q9y3o3"
python nltkdownload.py
```

Or run:

```bash id="tm9x2t"
download_nltk.bat
```

---

## 3️⃣ Run the Django Server

```bash id="y48u3w"
python manage.py runserver
```

---

## 4️⃣ Open in Browser

```bash id="r9ab6q"
http://127.0.0.1:8000/
```

---

# 🎯 Learning Outcomes

This project helped improve my understanding of:

* Machine Learning for Text Classification
* Natural Language Processing (NLP)
* Django Web Development
* Frontend & Backend Integration
* Database Management
* Model Evaluation & Prediction Systems

---

# 👩‍💻 Author

**Ashritha**

🔗 GitHub:
https://github.com/ashritha-16

---

# ⭐ Support

If you like this project, please give it a star ⭐
