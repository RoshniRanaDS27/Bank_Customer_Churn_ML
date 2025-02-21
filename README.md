# Bank Customer Churn Prediction with Advanced Machine Learning & Streamlit 💡💵
This project predicts whether a bank customer will churn (leave) or stay using cutting-edge machine learning techniques. It includes comprehensive data preprocessing, advanced model training, and a sleek Streamlit web application for real-time predictions.

# 📚 Table of Contents
1. Overview
2. Project Structure
3. Setup and Installation
4. How to Run
5. Features
6. Results
7. Technologies Used
8. Contributing

# 🔍 Overview
Customer churn prediction is crucial for financial institutions to enhance customer retention and profitability. This project leverages a robust machine learning pipeline featuring XGBoost, LightGBM, and Neural Networks for high-accuracy predictions. It also provides an intuitive Streamlit web app for live customer churn predictions.

# 🛠 Setup and Installation
Prerequisites:  
Python 3.8 or higher  
Jupyter Notebook  
pip or conda for package management  
  
Install Dependencies:
pip install -r requirements.txt

# 🚀 How to Run
✅ Run the Notebook for Analysis & Model Training

## jupyter notebook
Navigate to Bank_Churn_Prediction_Analysis.ipynb and run all cells for EDA, feature engineering, and model training.

# 🌐 Run the Streamlit Web App for Real-Time Predictions
Ensure the trained model (final_churn_model.pkl) is in the models/ directory.  
Launch the app:  
streamlit run app/streamlit_app.py  
Enter customer details in the web form and click Predict for instant feedback:  
🚨 Exit: Customer likely to churn.  
✅ No Exit: Customer likely to stay.  
  
# 🎯 Features
## 🤖 Machine Learning Pipeline
Data preprocessing: Handling missing values, outlier removal, and feature scaling.  
Feature engineering with PCA for dimensionality reduction.  
Multiple ML models tested:  
XGBoost  
LightGBM  
Neural Networks (Keras)  
XGBoost selected as the best model with 89% accuracy.  
  
# 🌟 Interactive Web App
Developed using Streamlit for real-time, web-based predictions.    
Clean UI with dynamic feedback:  
🟥 Exit (Red): High churn risk  
🟩 No Exit (Green): Low churn risk  
📈 Results  
## Best Model: XGBoost with 89% accuracy on the test set.  
F1 Score: 0.86  
AUC-ROC Score: 0.91  
Real-time prediction capability via Streamlit.  
  
# 🖥 Technologies Used
Languages & Frameworks: Python (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Keras)    
Visualization: Matplotlib, Seaborn, Plotly  
Deployment: Streamlit  
Model Serialization: joblib  
Other Tools: Git, Jupyter Notebook  
  
# 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.  
Let me know if you’d like Python code snippets for specific sections (e.g., XGBoost training, Streamlit app) or want to explore deployment options like Heroku or AWS EC2. 🚀💡  
