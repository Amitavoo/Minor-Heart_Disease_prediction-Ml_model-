{
  "title": "Heart Disease Prediction System (ML + Streamlit)",
  "description": "A machine learning-powered web application that predicts the risk of heart disease based on user health parameters. Built using K-Nearest Neighbors (KNN) and deployed with Streamlit, this project demonstrates an end-to-end ML pipeline.",
  
  "overview": "This application allows users to input medical attributes such as age, cholesterol, heart rate, etc., and get an instant prediction of whether they are at high risk or low risk of heart disease.",
  
  "tech_stack": [
    "Python",
    "Pandas",
    "Scikit-learn",
    "Streamlit",
    "Joblib"
  ],
  
  "features": [
    "Interactive UI using Streamlit",
    "Real-time prediction",
    "Pre-trained ML model (KNN)",
    "Feature scaling using StandardScaler",
    "Handles categorical inputs dynamically",
    "Clean and minimal design"
  ],
  
  "input_parameters": [
    "Age",
    "Sex",
    "Chest Pain Type",
    "Resting Blood Pressure (mm Hg)",
    "Cholesterol (mg/dl)",
    "Fasting Blood Sugar",
    "Resting ECG",
    "Max Heart Rate",
    "Exercise-Induced Angina",
    "Oldpeak",
    "ST Slope"
  ],
  
  "output": {
    "high_risk": "High risk of heart disease",
    "low_risk": "Low risk of heart disease"
  },
  
  "project_structure": {
    "app.py": "Streamlit application",
    "KNN_heart.pkl": "Trained KNN model",
    "scaler.pkl": "StandardScaler object",
    "X.columns.pkl": "Feature column structure",
    "README.md": "Project documentation"
  },
  
  "run_locally": [
    "git clone https://github.com/your-username/your-repo-name.git",
    "cd your-repo-name",
    "pip install -r requirements.txt",
    "streamlit run app.py"
  ],
  
  "future_improvements": [
    "Add more ML models (Logistic Regression, Random Forest)",
    "Deploy on cloud (AWS / Streamlit Cloud)",
    "Show prediction probability",
    "Add model evaluation metrics (Accuracy, ROC-AUC)"
  ],
  
  "author": {
    "name": "Amitava Mondal",
    "role": "Aspiring AI Engineer | ML Enthusiast"
  }
}
