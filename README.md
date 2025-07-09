# MediBot – An AI-Powered Health Assistant

**MediBot** is a web-based application that predicts possible diseases based on user-input symptoms using a machine learning model trained on real-world data. The system also includes tools for tracking BMI, estimating daily calorie needs, and generating personalized health reports.

This project was developed end-to-end by **Sanskruti Tayade** as a practical exploration of applied machine learning in healthcare.

---

## Features

- **Symptom-based Disease Prediction** using Random Forest
- **Chatbot Interface** for guided user input
- **NLP-based Symptom Matching** with Cosine Similarity
- **BMI & Calorie Estimation** based on user profile
- **Health Report Generation** in plain text format
- **Live Medical Info** fetched via DuckDuckGo search
- **User Registration & Login** with SQLite database

---

## Technologies Used

- **Programming Language**: Python  
- **Framework**: Flask  
- **Machine Learning**: scikit-learn, Pandas, joblib  
- **Natural Language Processing**: CountVectorizer, Cosine Similarity  
- **Frontend**: HTML, CSS, Jinja2 Templates  
- **Database**: SQLite

---

## Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/MediBot.git
cd MediBot
```

Install the required packages

```bash
pip install -r requirements.txt
Run the application
```

```bash
python app.py
Visit http://localhost:3000 in your browser to use the app.
```
---

## Project Structure

MediBot/
├── app.py                  # Main Flask app
├── classes/                # Core logic for User, Food, Report
├── dataset/                # CSV files for training data
├── model/                  # Saved ML models (.joblib)
├── notebook/               # Jupyter notebook for model training
├── templates/              # HTML templates
├── static/                 # CSS, images, and assets
└── database.db             # SQLite database

---

## About the Creator
Sanskruti Tayade
```AI/ML Developer based in Pune, India```

This project was designed, developed, and tested independently to apply machine learning in a meaningful domain. I focused not just on the accuracy of prediction, but also on user interaction, explainability, and practical health guidance.
