📊 Model Interpretability Using SHAP



Adult Income Classification with XGBoost

📌 Project Overview



This project demonstrates how SHAP (SHapley Additive exPlanations) can be used to interpret a machine learning model trained on the Adult Income dataset.



The objective is to predict whether an individual's annual income exceeds $50K using demographic and employment-related features. Beyond predictive performance, the primary focus of this project is to provide transparent and interpretable insights into the model’s behavior.



🎯 Objectives



Train an XGBoost classifier on the Adult Income dataset



Achieve strong predictive performance (AUC > 0.80)



Apply SHAP for global and local interpretability



Derive meaningful business insights from model explanations



📂 Dataset Description



The dataset includes the following features:

age

workclass

fnlwgt

education

education.num

marital.status

occupation

relationship

race

sex

capital.gain

capital.loss

hours.per.week

native.country

income (Target Variable)

Target Variable:

0 → Income ≤ 50K

1 → Income > 50K



🛠 Technologies Used

Python 3.9

XGBoost

SHAP

Scikit-learn

Pandas

NumPy

Matplotlib

Seaborn



⚙️ Installation \& Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/your-repository-name.git

cd your-repository-name



2️⃣ Create environment

conda create -n shap\_env python=3.9

conda activate shap\_env



3️⃣ Install dependencies

pip install -r requirements.txt



4️⃣ Run the notebook

jupyter notebook





Open SHAP\_visualizations.ipynb and run all cells from top to bottom.



📈 Model Performance



Accuracy: 0.8627548483341622



AUC Score: 0.9208197661592765 (Greater than 0.80)



The model successfully meets the required performance threshold.



🔍 SHAP Interpretability Analysis



The following SHAP visualizations were generated:



✅ SHAP Beeswarm Plot (Global Impact)



✅ SHAP Bar Plot (Feature Importance Ranking)



✅ SHAP Dependence Plot (Feature Interaction)



✅ SHAP Waterfall Plot (Individual Prediction Explanation)



Key Findings:



Capital Gain is the most influential feature in predicting high income.



Higher education levels significantly increase income probability.



More hours worked per week positively impact income classification.



Marital status and relationship features also contribute to predictions.



These insights highlight the strong influence of investment income, education, and work intensity on income levels.



💡 Business Insights



The analysis reveals that non-salary income (capital gains) plays a critical role in classifying individuals into the higher income category. Educational attainment and work commitment also significantly influence income outcomes. This suggests structural economic patterns where asset ownership and human capital strongly determine earning potential.



SHAP enhances transparency by clearly showing how each feature contributes to both global model behavior and individual predictions.



🎥 Video Walkthrough



A short (3–5 minute) project walkthrough is available here: 



👉 \[Insert YouTube or Vimeo Link Here]



📁 Repository Structure

├── SHAP\_visualizations.ipynb

├── requirements.txt

├── README.md

└── dataset.csv (if included)



✅ Conclusion



This project demonstrates how integrating SHAP with XGBoost provides both strong predictive performance and transparent model interpretability. The combination of global and local explanations enables deeper understanding of the drivers behind income classification.



📜 License



This project is for educational and evaluation purposes.

