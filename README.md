# SmartRx-Your Personal Health Assistant
**SmartRx** is a Personalized Medical Recommendation System designed to help users understand and manage their health. Leveraging advanced machine learning models, SmartRx analyzes user-input symptoms to predict potential diseases and provides tailored recommendations for medications, prescriptions, and wellness routines.

## Features

- **User-Friendly Interface:** Easily input your symptoms and navigate the system.
- **Accurate Disease Predictions:** State-of-the-art machine learning models predict diseases based on symptoms.
- **Personalized Health Recommendations:** Receive top 5 medicine suggestions, prescription guidance, and workout recommendations tailored to your condition.
- **Flask Web App Integration:** Access SmartRx from any browser for convenient healthcare insights.
- **Privacy & Security:** All user data is handled securely and confidentially.
- **Continuous Learning:** The system improves over time as more data is collected, providing more accurate predictions.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Malick-07/SmartRx---Your-Personal-Health-Assistant.git
cd SmartRx---Your-Personal-Health-Assistant
Create a virtual environment:
python -m venv venv

Activate the virtual environment:

PowerShell (Windows):
.\venv\Scripts\activate
Command Prompt (Windows):
venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Running the Application
streamlit run app.py

Open your browser at http://localhost:8501 to use SmartRx.

Project Structure

app.py — Main Streamlit application

train_model.py — Script to train disease prediction model

train_heart_model.py — Script to train heart disease prediction model

diabetes_model.pkl, heart_model.pkl — Pre-trained machine learning models

requirements.txt — Python dependencies

.gitignore — Ignore unnecessary files

