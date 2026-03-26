🚀 Insurance Cost Analysis
📊 EDA | Feature Engineering | Statistical Testing | ML-Ready Dataset



🧠 Problem Statement

Medical insurance costs vary significantly across individuals.
This project aims to identify key factors driving insurance charges using data analysis and statistical validation.

🎯 What Makes This Project Stand Out

✔️ Real-world dataset analysis
✔️ Strong EDA with visual insights
✔️ Feature engineering using domain knowledge
✔️ Statistical testing (Chi-Square + Correlation)
✔️ Clean ML-ready dataset

📂 Dataset Overview
Feature	Description
age	Age of individual
sex	Gender
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential region
charges	Insurance cost (target)
🔍 Workflow
📌 1. Data Exploration
Distribution analysis (histograms, KDE)
Categorical analysis (countplots)
Outlier detection (boxplots)
🧹 2. Data Cleaning
Removed duplicates
Verified missing values
⚙️ 3. Feature Engineering
Encoded categorical variables
Created BMI Category Feature:
Underweight
Normal
Overweight
Obese
📏 4. Feature Scaling
Applied StandardScaler to numerical features
📊 5. Statistical Analysis
Pearson Correlation → numerical relationships
Chi-Square Test → categorical importance
📈 Key Insights (🔥 Recruiter Hook Section)

🚬 Smoker = Highest Cost Driver
→ Smokers are charged significantly higher insurance

⚖️ BMI Matters
→ Obesity strongly increases medical costs

👴 Age Factor
→ Older individuals tend to have higher charges

🌍 Low Impact Features
→ Gender and region have minimal effect

🧠 Final Conclusion

Lifestyle factors (especially smoking and obesity) have a far greater impact on insurance charges than demographic factors.

📊 Before vs After (Impact of Feature Engineering)
Step	Improvement
Raw Data	Unstructured
After Encoding	Model-friendly
After Engineering	More informative features
Final Dataset	ML-ready 🚀
🚀 Future Scope
Build regression models (Linear Regression, Random Forest)
Hyperparameter tuning
Outlier handling
Deploy as a web app (Flask/Streamlit)
📁 Project Structure
├── Project 1.ipynb
├── dataset.csv
├── README.md
