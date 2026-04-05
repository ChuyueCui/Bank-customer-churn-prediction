# 🏦 Bank Customer Churn Prediction (Machine Learning)

📌 Project Overview  
This project focuses on predicting customer churn for a bank using machine learning techniques. The goal is to identify at-risk customers early and support data-driven retention strategies.

🔍 Key Contributions  
- Performed exploratory data analysis (EDA) to understand customer behavior and churn patterns  
- Conducted feature engineering, including scaling numerical features and encoding categorical variables  
- Built and compared multiple models, including Logistic Regression, Random Forest, Gradient Boosting, MLP, and XGBoost/LightGBM/CatBoost  
- Applied threshold tuning to balance recall and precision for better business outcomes  

📊 Business Impact & Insights  
- Higher recall helps identify more at-risk customers, improving retention efforts  
- Trade-off between precision and recall impacts operational cost and customer targeting strategy  
- Features such as age, activity status, and balance showed strong influence on churn behavior  

🏆 Results  
- Achieved strong model performance with AUC around 0.80 across models  
- Optimized CatBoost achieved highest accuracy (~84%)  
- Logistic Regression with adjusted threshold achieved highest recall (~79%), supporting proactive retention strategies  

🛠️ Tools & Technologies  
- Python  
- scikit-learn, XGBoost, LightGBM, CatBoost  
- Data preprocessing & feature engineering  
- Model evaluation (ROC-AUC, precision, recall, F1-score)


📄 Project Resources  
- 📄 Report: [View Report](./customer_churn_analysis_report.pdf)  
- 📊 Presentation: [View Slides](./customer_modeling_presentation.pdf)  
- 💻 Code: [View Notebook](./churn_modeling.ipynb)      
