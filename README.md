❤️ Heart Disease Prediction Project
📌 Project Overview
This project predicts whether a patient is at risk of heart disease using Machine Learning models.  
It includes a **Streamlit web app** that allows users to input patient details and instantly get predictions.


🚀 Features
- Predicts Heart Disease Risk (Healthy ✅ / At Risk ⚠️)  
- Trained with Random Forest Classifier** for high accuracy  
- Streamlit app for interactive predictions  
- Supports custom patient input data  


 🛠️ Technology Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Streamlit  
- Joblib  


 📂 Project Structure

├── heart_rf_model.pkl       # Trained Random Forest model
├── heart_scaler.pkl         # Scaler for preprocessing
├── model_columns.pkl        # Feature columns used during training
├── heart_user_template.csv  # Sample input file
├── streamlit_app.py         # Streamlit web app
├── deseasepredict.py        # Main ML workflow
└── README.md                # Project documentation


⚙️ Installation
1. Clone this repository  
bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction


2. Install dependencies  
bash
pip install -r requirements.txt


 ▶️ Usage
Open Colab Notebook:
Run the Disease_Detector.ipynb file step by step.
Train the model and generate predictions.
(Optional) Use the saved model (.pkl file) for deployment in other applications.
Run the Streamlit app with:  
bash
streamlit run streamlit_app.py


- Enter patient details in the sidebar  
- Click **Predict**  
- Get instant results: *Healthy ✅* or *At Risk ⚠️*  

🙌 Acknowledgements
- Dataset: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
