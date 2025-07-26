# 🩺 Diabetes Risk Prediction – Machine Learning Web App

This project predicts the risk of diabetes in an individual using machine learning. The app is built using **Streamlit** for the user interface and deployed-ready using **Render** or similar platforms.

## 🔍 Problem Statement
Predict whether a patient is likely to be diagnosed with diabetes based on diagnostic measurements such as glucose level, BMI, age, etc.

## 📊 Dataset
- **Name:** Pima Indians Diabetes Database  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Features:**  
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Target: 0 = No Diabetes, 1 = Diabetes)

## 🚀 Technologies Used
- Python
- Scikit-learn
- Streamlit
- Pandas, NumPy
- Joblib (for model saving)

## 📦 Installation

1. Clone the repo:
git clone https://github.com/your-username/diabetes-prediction-ml-app.git
cd diabetes-prediction-ml-app

markdown
Copy
Edit

2. Install dependencies:
pip install -r requirements.txt

markdown
Copy
Edit

3. Add the dataset `diabetes.csv` to the project root folder.

4. Train the model:
python train_model.py

markdown
Copy
Edit

5. Run the app:
streamlit run app.py

markdown
Copy
Edit

## 🧠 Model
- **Algorithm:** Random Forest Classifier
- **Pipeline:** Scaler + Classifier
- **Accuracy:** ~80% (may vary)

## 🌐 Deployment
This app can be deployed to platforms like:
- [Render](https://render.com/)
- Hugging Face Spaces (Gradio/Streamlit)
- Heroku (deprecated free tier)
- Streamlit Community Cloud

## 📸 App Preview

![App Screenshot](./screenshot.png)

## 📬 Connect with Me

**Nikita Bhosage**  
👩‍💻 Aspiring Data Analyst | AI-ML Enthusiast  
📧 [YourEmail@email.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile) | [GitHub](https://github.com/your-username)

---
