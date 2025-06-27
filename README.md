WageWizard 💼✨

Overview: 
WageWizard is a machine learning project designed to help fresh graduates and job seekers estimate their expected salary based on their education, experience, and role. 
It uses a robust end-to-end ML pipeline and a Random Forest Regressor to deliver accurate, personalized salary predictions in seconds.

This project demonstrates:
  A complete ML workflow (EDA, preprocessing, modeling, deployment)
  An interactive approach to salary benchmarking
  Practical insights for students and career services

Business Problem:
Graduates and early-career professionals often face:
  Unclear salary expectations
  Anxiety about the job market
  Lack of personalized guidance
  
WageWizard addresses this by providing:
  Realistic salary ranges based on real-world data
  Data-driven advice for profile improvement
  An interactive tool to support career decisions

File	Description:
AD.ipynb	Jupyter Notebook for EDA and preprocessing
AD_project (1).ipynb:	Jupyter Notebook for model building and evaluation
Salary_Data.csv:	Cleaned dataset used for training the model
preprocessor.pkl:	Saved preprocessor for consistent data transformation
salary_predictor_rf_model.pkl:	Final trained Random Forest model
WAGEWIZARD_Pitch_Deck.pdf:	Project pitch deck summarizing the solution, results, and next steps
Machine Learning Canvas.pdf:	Detailed ML canvas outlining business context, decisions, and deployment strategy
Final DEMO.mp4: 	Demo video showing the project in action

Key Features
  Supervised Regression Model
  Random Forest Regressor (R² = 0.98)
  End-to-End Pipeline: EDA → Modeling → Deployment
  Streamlit-ready for interactive predictions
  Personalized insights and profile improvement tips

How it Works:
Data Preparation:
  Real-world salary dataset from Kaggle
  Cleaned and preprocessed (missing values handled, categorical features encoded, numerical features scaled)
EDA:
  Identified key salary drivers: experience, education, role
Model Building:
  Tested Linear Regression, XGBoost, and Random Forest
  Random Forest selected for best performance (R² = 0.98, MAE ≈ $2,880)
Deployment:
  Model and preprocessor exported as .pkl files
  Ready for integration with a Streamlit app

License:
  Distributed for academic and educational purposes.
