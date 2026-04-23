📧 Spam Detection System (Web + Machine Learning)

A dual-mode Spam Detection System that classifies messages as Spam or Ham (Legitimate) using both a Machine Learning model (Python) and a modern Web Application (React).

🚀 Project Overview

This project demonstrates a complete end-to-end system:
🌐 Web Application: Interactive UI for spam detection (frontend demo)
🐍 Python ML Model: Real machine learning pipeline for training and prediction

🏗️ Tech Stack
  🌐 Web Application
      React (Vite)
      TypeScript / JavaScript
      Tailwind CSS
      Lucide React Icons
      Netlify (Deployment)
      
  🐍 Machine Learning Model
      Python
      Scikit-learn
      NLTK
      Pandas
      NumPy
      Matplotlib / Seaborn
      Streamlit
      
🤖 How It Works
      1. Text Input
        User enters a message (SMS / email text)
      2. Feature Extraction
        System detects:
        Spam keywords (free, winner, urgent, prize)
        URLs and phone numbers
        ALL CAPS words
        Excess punctuation
     3. Prediction
        ML model or rule-based logic classifies text
        Output: Spam / Ham
        Confidence score is displayed
🧠 Machine Learning Pipeline
  📌 Data Preprocessing
      Lowercasing text
      Removing URLs, emails, special characters
      Tokenization
      Stopword removal
      Stemming
      TF-IDF Vectorization
  📌 Model Training
      Algorithms used:
        Naive Bayes
        Logistic Regression ⭐ (Best Accuracy: 98.1%)
        SVM
        Random Forest
  📌 Evaluation Metrics
        Accuracy
        Precision
        Recall
        F1 Score
        Confusion Matrix
📊 Dataset
    Dataset: SMS Spam Collection Dataset
    Source: UCI Machine Learning Repository
    Total Messages: 5,574
    Split: 80% Training / 20% Testing

🏆 Results
    Accuracy: 98.1%
    Precision: 97.3%
    Recall: 95.8%
    F1 Score: 96.5%
    
💻 Project Versions
  🌐 Web Version
      Frontend-only simulation
      Instant spam detection
      UI/Portfolio demonstration
      Hosted on Netlify
  🐍 Python Version
      Full ML implementation
      Model training and evaluation
      Streamlit UI
      Academic submission

🔄 Key Features
    Real-time spam detection
    Confidence score display
    Clean and modern UI
    ML-based classification
    Dual implementation (Web + Python)

📌 Future Improvements
    Deep Learning (LSTM / BERT)
    Flask / FastAPI backend integration
    Mobile application version
    Cloud deployment
    Multi-language support

👨‍💻 Team Members
P. Lahari
📧 Email: laharireddypa06@gmail.com
K. Anagha
📧 Email: anagharaju05@gmail.com
M. Harikrishna
📧 Email: mukthalahari9948@gmail.com
B. Sai
📧 Email: banothusai17s@gmail.com

⭐ How to Run
  🐍 Python Version
          pip install -r requirements.txt
          python app.py
  🌐 Web Version
          npm install
          npm run dev
