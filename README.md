# MediTrain_AI


## Overview

MediTrain AI is an advanced medical assistant designed to revolutionize healthcare by providing intelligent, accurate, and personalized solutions. 
It empowers both doctors and patients by leveraging advancements in Artificial Intelligence and Natural Language Processing. With MediTrain AI, 
users can experience seamless interaction, real-time diagnosis, tailored treatment suggestions, and communication that bridges the gap 
between technology and healthcare. Step into the future of healthcare with MediTrain AI and transform the way you experience medical assistance!

## Features

* **Conversational Context** : Retains the context of recent interactions to provide relevant and cohesive responses.
* **Medical Focus** : Tailored to assist with general medical questions while avoiding direct diagnoses.
* **Flask UI** : Interactive web-based interface for seamless user interaction, using HTML, CSS and JavaScript for responsiveness and styling.
* **Empathetic Responses** : Ensures responses are clear, considerate, and accurate.
* **Real-Time Query Handling** : Processes and responds to medical queries quickly using AI models for fast, accurate answers.
* **Personalized Guidance** : Adapts responses based on user interactions, offering relevant insights for recurring topics or conditions.
* **Secure and Private** : Ensures user privacy with secure handling of interactions and secure storage of personal health data.
* **Dual Purpose ChatBot** : Meditrain AI has both doctor and patient Chat facilities.
* **Profile** : Meditrain AI has Profile and History pages to track previous diagonsis,  which requires user to login.
* **Quick Chat** : Allows user to access the Chat without login, but cannot accsess Profile and Hisory.
* **Database Connectivity** : Uses Sqlite database for store user data and history.
  
## Prerequisites

To run MediTrain AI locally, ensure you have the following:

* Python 3.8+
* Libraries specified in `requirements.txt`

## Manual Installation

1. Clone this repository :
   ```bash
   git clone https://github.com/Nishok-12/MediTrain_AI.git
   cd Final_projects
   ```
2. Create a virtual environment and activate it :
   ```bash
   python -m venv venv
   source venv\Scripts\activate  # On Linux: venv/bin/activate
   ```
3. Install the dependencies :
   ```bash
   pip install -r requirements.txt
   ```

## Running Manually

1. Run the application :
   ```bash
   python app.py
   ```
2. Open the application in your browser (default: [http://localhost:9999](http://localhost:9999/)).
3. Interact with MediTrain AI by typing your medical queries in the input box.

## Online hosting

* **Render** : Render is a modern cloud web service that allows developers to host websites, APIs, and apps effortlessly. It provides features like **auto-deploy from Git, free SSL, custom domains, managed databases**, and scalability options, catering to both static and dynamic applications with an intuitive interface.

## Access Online

*  Enjoy Accessing my MediTrain AI seamlessly at the link [MediTrain_AI](https://meditrain-ai-v3mj.onrender.com).
**(OR)**
* Copy paste the below link in your browser
     ```bash
   https://meditrain-ai-v3mj.onrender.com
   ```
  

## Project Structure
   ```
  MediTrain-AI/                                  # Main Project Folder 
  │
  ├── Agile Documentation/                       # Folder for Agile Documents
  │   └── Agile Document.xlsx                    # Main Excel file containing Sprint details of this Project  
  │
  ├── Datasets/                                  # Folder for the Datasets used in the Project
  │   ├── Actual_doenloaded_datasets/            # Folder for actual downloaded datasets from Kaggle
  │   └── Modified_datasets/                     # Folder for modified datasets from downloaded dataset
  │
  ├── Final_project/                             # Folder for final working elements
  │   ├── instance/                              # Forlder for database
  │   ├── static/                                # Folder for static files
  |   |   ├── css/                               # Folder for CSS files
  |   |   ├── dataset/                           # Folder for live used datasets
  |   |   └──model/                              # Floder for Saved model files to load into Flask app
  |   | 
  │   ├── templates/                             # Folder for HTML templates
  │   ├── app.py                                 # Main Flask application script
  │   └── requirements.txt                       # List of required Python packages
  │
  │
  ├──Models/                                     # Folder for Code of Model training,saving and testing 
  │   ├── Doctor Model/                          # Folder for Doctor_chat-related model files
  │   └── Patient Model/                         # Folder for Patient_chat-related model files
  │
  ├── LICENSE                                    # MIT License for the project            
  └── README.md                                  # Project documentation
   ```

## Key Libraries

* **Flask** : A lightweight Python web framework for building web applications and APIs.
* **Flask-SQLAlchemy** : Adds SQLAlchemy support to Flask, making it easier to interact with databases.
* **Flask-Migrate** : Handles database migrations for Flask applications, simplifying the management of changes to the database schema.
* **Pandas** : A powerful library for data manipulation and analysis, particularly useful for handling structured data like CSV, Excel.
* **Fuzzywuzzy** : A library for string matching and fuzzy searching, often used for comparing text and determining similarities between them.
* **Scikit-learn** : A machine learning library that provides simple and efficient tools for data mining and data analysis,and ML Algorithms. 
* **Joblib** : A library for serializing Python objects, used for saving and loading machine learning models and large datasets efficiently.

## Models Utilized

- **No Use Of Pretrained Models** : No Pre-Trained model is used in this project.
- **Build from Scratch** : All models used in this project are build from scratch.
* **Logistic Regression** : Used for prediction of Diseases,Treatments and Symptoms.
* **Random Forest Classifier** : Used for prediction of Treatments.

## Dataset Utilized

 **Kaggle** : Datasets are taken from kaggle ( [Dataset Link](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset/data)).

## Database Utilized

**Sqlite3** : A lightweight, file-based relational database engine, ideal for small to medium-sized applications. It is self-contained, serverless, and requires no separate setup, making it perfect for quickly prototyping and managing local data in your project.

## Important Notes

* **No Medical Diagnoses** : MediTrain AI is for Medical assitance and may not provide accurate Diagonosis .
* **Consult Professionals** : Always seek advice from certified healthcare professionals for medical concerns.
* **Not a Substitute for Medical Care** : MediTrain AI is an assistant, not a replacement for professional healthcare.
* **Use Responsibly** : The information provided should be used as a guide, not as a definitive answer.

## Future Enhancements

* **Multilingual Support** : Enable the chatbot to handle multiple languages.
* **Conversation Memory** : Retain context for personalized responses over time.
* **Region-Specific Advice** : Offer localized medical information based on user location.
* **Symptom Tracker** : Allow users to log and track symptoms for better monitoring.
* **Voice Input** : Enable voice interaction for hands-free use.
* **Real-Time Data** : Integrate wearable device data for tailored health advice.

## License

This project is licensed under the MIT License.

----

#### Enjoy using MediTrain AI and let us know if you have suggestions or encounter issues!
