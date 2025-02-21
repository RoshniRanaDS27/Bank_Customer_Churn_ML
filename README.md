![image](https://github.com/user-attachments/assets/28f45572-735d-45f4-852a-b83510cb4062)

# Bank Customer Churn Prediction with Advanced Machine Learning & Streamlit 💡💵
This project predicts whether a bank customer will churn (leave) or stay using cutting-edge machine learning techniques. It includes comprehensive data preprocessing, advanced model training, and a sleek Streamlit web application for real-time predictions.

![image](https://github.com/user-attachments/assets/e82f59b6-b849-40d2-9dff-377d662a0b81)

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
![image](https://github.com/user-attachments/assets/28eff584-7bea-4b58-b34e-884217cf5873)


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

![image](https://github.com/user-attachments/assets/7c9d5d25-52a0-4b44-804a-610981562ad0)

  
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
## Best Model: RF with 87% accuracy on the test set.  
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

# 🚀 Developing an AI-Driven Solution for #BankCustomerChurnPrediction!

I'm excited to present my latest addition to the Machine Learning Series: Bank Customer Churn Prediction 🏦📊. This project was a remarkable experience, exploring data preprocessing, feature engineering, and advanced machine learning methods to address a crucial business challenge—predicting whether a customer will stay with the bank or churn.

# 🌟 Key Highlights
📌 Dataset:  
The dataset comprised customer demographics, account information, and behavioral attributes.  

# 📌 Preprocessing Steps:
Dropped non-informative columns like RowNumber, CustomerId, and Surname that had no predictive significance.  
Performed one-hot encoding on categorical features (Geography and Gender), ensuring the dummy variable trap was avoided.  
Scaled numerical features such as CreditScore, Balance, and EstimatedSalary for consistency across the dataset.  
# 📌 Insights Gained:
Identified data imbalance in churn distribution, with fewer customers leaving compared to those staying (SMOTE was used to balance the dataset).  
Key predictors included Age, Tenure, and Balance, as identified through a correlation matrix analysis.  
# 📌 Model Development:
Trained and evaluated multiple classification models:  
Logistic Regression  
Random Forest  
Gradient Boosting  
## 🏆 Random Forest delivered the best performance with 87% accuracy, balancing precision and recall effectively.  

# 📌 GUI for Real-Time Predictions:
Built an interactive GUI using Tkinter for user-friendly predictions.  
Users can input customer details and receive instant predictions on churn risk.  
Visual feedback integrated with clear labels:  
🔴 Exit: Customer likely to churn.  
🟢 Stay: Customer likely to remain.  
# 📌 Business Impact:  
Proactively identifies customers at risk of leaving.  
Supports targeted retention strategies, potentially saving millions in acquisition costs.  
# 📌 Key Findings:  
📊 Older customers and those with high balances but low engagement are more likely to churn.  
📊 Geography and gender significantly influence churn probability, emphasizing the need for localized strategies.  

# 💡 Key Takeaways
This project sharpened my technical skills and enhanced my understanding of customer behavior in real-world scenarios. I gained practical experience in:  

Managing imbalanced datasets  
Applying feature scaling techniques  
Developing user-friendly ML applications  
# 🚀💡 This journey into AI-powered churn prediction highlighted how machine learning can drive strategic decision-making in the banking sector.  
