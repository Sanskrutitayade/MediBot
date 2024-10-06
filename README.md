
# MediBot

MediBot is an AI-powered healthcare chatbot designed to assist users with symptom analysis, disease prediction, and hospital recommendations. The chatbot leverages Natural Language Processing (NLP) to interact with users and provide accurate healthcare insights based on the user’s input. MediBot is built with Python, Flask, and SQLite, and integrates AI and NLP algorithms to enhance user experience.

## Features
- **Symptom Analysis**: Input symptoms to get potential disease predictions.
- **Disease Prediction**: Uses AI models to predict the most likely diseases based on symptoms.
- **Hospital Recommendations**: Provides nearby hospital suggestions based on the user's location.
- **NLP Integration**: Enhances conversation quality and improves response accuracy.
- **User-Friendly Interface**: Designed with HTML/CSS/JS for a seamless user experience.
- **Data Management**: User data, including symptom tracking and hospital info, is securely managed in the backend.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Database**: SQLite
- **AI/ML Libraries**: 
  - Natural Language Processing (NLP)
  - TensorFlow (for AI/ML models)
- **Other Libraries**:
  - Pandas, NumPy (for data processing and analysis)

## Installation

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Flask
- SQLite
- Required Python libraries (listed in `requirements.txt`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Sanskrutitayade/MediBot.git
   cd MediBot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask server:
   ```bash
   python app.py
   ```

4. Open your browser and navigate to `http://127.0.0.1:5000/` to interact with MediBot.

## Project Structure
```
MediBot/
│
├── app.py                  # Main Flask application file
├── templates/              # HTML templates for the UI
│   └── index.html          # Main HTML page
├── static/                 # Static files like CSS, JS, and images
│   └── style.css           # Stylesheet for the UI
├── models/                 # AI models for disease prediction
├── database/               # SQLite database and related files
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies
```

## Usage
1. Open the chatbot interface in your browser.
2. Input your symptoms in plain text, and MediBot will analyze them to predict possible diseases.
3. Based on the predicted diseases, MediBot will recommend nearby hospitals for treatment.
4. The chatbot learns over time and improves its predictions based on user inputs.

## Future Improvements
- **Expand Disease Prediction**: Adding more diseases to the model to increase prediction accuracy.
- **Mobile App**: Developing a mobile version of MediBot for wider accessibility.
- **Voice Integration**: Incorporating voice-based interactions for users who prefer verbal input.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **NLP Library**: Natural Language Toolkit (NLTK)
- **AI Framework**: TensorFlow
- Special thanks to everyone who contributed to this project.
