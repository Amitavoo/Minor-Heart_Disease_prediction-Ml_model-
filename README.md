❤️ Heart Disease Prediction System (ML + Streamlit)

A machine learning-powered web application that predicts the risk of heart disease based on user health parameters. Built using a K-Nearest Neighbors (KNN) model and deployed with an interactive Streamlit UI, this project demonstrates end-to-end ML workflow — from preprocessing to real-time inference.

🚀 Features
🔍 Real-time Prediction using trained ML model
📊 User-friendly UI built with Streamlit
⚙️ Preprocessing Pipeline with feature scaling
🧠 KNN Model for classification
📁 Serialized Models using joblib
🧩 Handles categorical encoding dynamically
🧠 Machine Learning Pipeline
Data Preprocessing
Handling categorical variables using one-hot encoding
Feature scaling using StandardScaler
Model Training
Algorithm: K-Nearest Neighbors (KNN)
Saved as: KNN_heart.pkl
Deployment
Built with Streamlit
Takes real-time user input and predicts risk
🖥️ Input Features

The model takes the following medical attributes:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Fasting Blood Sugar
Resting ECG
Max Heart Rate
Exercise-Induced Angina
Oldpeak (ST depression)
ST Slope
📦 Project Structure
├── app.py                # Streamlit app
├── KNN_heart.pkl        # Trained ML model
├── scaler.pkl           # Feature scaler
├── X.columns.pkl        # Expected feature columns
├── README.md            # Project documentation
▶️ Run Locally
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git

# Navigate to project
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
📊 Output
🟢 Low Risk of Heart Disease
🔴 High Risk of Heart Disease
💡 Key Highlights
Ensures correct feature alignment using expected_columns
Prevents missing feature errors dynamically
Clean and minimal UI for better usability
Fully beginner-to-intermediate level ML deployment project
🎯 Future Improvements
🔥 Add model comparison (Logistic Regression, Random Forest, etc.)
🌐 Deploy on cloud (AWS / Streamlit Cloud)
📈 Show prediction probability instead of binary output
🧪 Add model evaluation metrics (Accuracy, ROC-AUC)
👨‍💻 Author

Amitava Mondal
Aspiring AI Engineer | ML Enthusiast
