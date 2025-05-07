# Medical Chatbot

## Project Owner: Phạm Lê Ngọc Sơn

## Project Overview
Medical Chatbot is an AI-driven conversational agent designed to interact with users, providing medical information, advice, and support through natural language processing (NLP). The application allows users to input their symptoms through a chat interface and receive preliminary diagnoses, descriptions of potential illnesses, and recommended precautions.

## Project Structure
```
Medical/
├── .git/                     # Git repository data
├── __pycache__/              # Python cache files
├── data/                     # Data files for the model
│   ├── list_of_symptoms.pickle
│   ├── symptom_Description.csv
│   ├── symptom_precaution.csv
│   └── Symptom-severity.csv
├── models/                   # Trained ML models
│   ├── data.pth              # PyTorch model data
│   └── fitted_model.pickle2  # Pickle model for prediction
├── static/                   # Static files for web app
│   ├── assets/               # Assets like images and data files
│   ├── css/                  # CSS stylesheets
│   └── js/                   # JavaScript files
├── templates/                # HTML templates
│   └── index.html            # Main chat interface
├── app.py                    # Main Flask application
├── intents.json              # NLP training data
├── intents_short.json        # Shorter version of NLP training data
├── LICENSE                   # License information
├── Meddy.ipynb               # Jupyter notebook with model training
├── nnet.py                   # Neural network implementation
├── nltk_utils.py             # Natural language toolkit utilities
└── README.md                 # Project documentation
```

## Technologies Used
- **Backend**: Python, Flask
- **Machine Learning**: PyTorch, scikit-learn, NLTK
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Data Processing**: Pandas, NumPy

## Features
1. **Interactive Chat Interface**: User-friendly interface for symptom input
2. **Symptom Recognition**: NLP-based symptom identification from user input
3. **Disease Prediction**: ML model to predict possible diseases based on symptoms
4. **Detailed Information**: Provides descriptions and precautions for identified diseases
5. **Severity Assessment**: Evaluates symptom severity and recommends professional help when necessary

## How to Use
1. **Setup Environment**:
   ```
   pip install -r requirements.txt
   ```

2. **Run the Application**:
   ```
   python app.py
   ```

3. **Interact with the Chatbot**:
   - Open a web browser and navigate to `http://localhost:5000`
   - Enter your symptoms one by one in the chat interface
   - Type 'Done' when you've entered all symptoms
   - The chatbot will provide a diagnosis with description and precautions

## Note
This application is intended for educational and informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

## Contact
For any queries or suggestions regarding this project, please contact:
- **Name**: Phạm Lê Ngọc Sơn
- **Email**: [contact information]

## License
This project is licensed under the terms of the license included in the repository.
