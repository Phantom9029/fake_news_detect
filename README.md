# fake_news_detect

📰 Fake News Detection System
A machine learning-powered web application to detect fake news articles using DistilBERT for NLP classification. The backend is built with Spring Boot, and the ML model is served via an inference pipeline.

📌 Features
✅ Detects whether a news headline/body is real or fake

🤖 Uses Logistic regression 



🚀 Technologies Used
Area	Tech Stack
ML/NLP	Python,  Scikit-learn




1. 🧠 Train the ML Model (Python)
bash
Copy
Edit
cd ml-model
pip install -r requirements.txt
python train.py


Saves the model to model/ directory (e.g., model/fake_news_model.pkl ).



json
Copy
Edit
{ "text": "The news article goes here." }
🧪 Example API Request
POST /api/predict

json
Copy
Edit
{
  "text": "NASA confirms water on the moon."
}
Response



