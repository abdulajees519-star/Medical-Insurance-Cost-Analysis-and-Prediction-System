#Medical Insurance Cost Analysis and Prediction System

##Overview

This project analyzes an insurance dataset and predicts medical insurance charges using Machine Learning techniques. It includes data preprocessing, visualization, exploratory data analysis (EDA), and predictive modeling using Linear Regression and Logistic Regression.

##Features
*Data loading and preprocessing
*Missing value checking
*Duplicate record removal
*Categorical data encoding using LabelEncoder
*Data visualization with Matplotlib and Seaborn
*Correlation analysis using Heatmap

##Insurance charge prediction used
*Linear Regression
*Multiple Linear Regression
*Logistic Regression
*Technologies Used
*Python
*Pandas
*NumPy
*Matplotlib
*Seaborn
*Scikit-learn
*Dataset

##The project uses the insurance.csv dataset containing

*Age
*Sex
*BMI
*Children
*Smoker
*Region
*Charges

##Project Workflow

### 1. Data Preprocessing


Load dataset.
Check missing values
Remove duplicate records
Encode categorical features

### 2. Exploratory Data Analysis

Visualizations created:

Age Distribution
-<img width="697" height="452" alt="WhatsApp Image 2026-06-17 at 12 53 43 PM" src="https://github.com/user-attachments/assets/e9b19edb-a8f7-4bab-b07b-416df091be37" />

BMI Distribution
-<img width="695" height="443" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM" src="https://github.com/user-attachments/assets/1469821f-2880-4d3f-9102-af4592764aa1" />

Insurance Charges Distribution
-<img width="710" height="462" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (1)" src="https://github.com/user-attachments/assets/8f5a08c5-0351-4990-819a-da88f94a3729" />

Age vs Charges
-<img width="717" height="482" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (2)" src="https://github.com/user-attachments/assets/6691486e-2363-4c5e-a71f-96fb8ff4dbd4" />

BMI vs Charges
-<img width="717" height="471" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (3)" src="https://github.com/user-attachments/assets/c9928ec1-f35d-4b4b-9afb-db759bef0a29" />

Smoker vs Charges
-<img width="721" height="467" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (4)" src="https://github.com/user-attachments/assets/9c1e6f7d-6902-4225-bcb9-cd62569c6659" />

Region-wise Charges
-<img width="712" height="463" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (5)" src="https://github.com/user-attachments/assets/6d9a7c3a-d97e-47c0-bb62-f6be1f9fa18d" />

Correlation Heatmap
-<img width="647" height="445" alt="WhatsApp Image 2026-06-17 at 12 53 44 PM (6)" src="https://github.com/user-attachments/assets/ff5deb44-84c5-4840-8cde-17f626918464" />

###3. Machine Learning Models
Linear Regression

Predicts insurance charges using age as the feature.

Multiple Linear Regression

Predicts insurance charges using:

Age
BMI
Children
Smoker Status
Logistic Regression

Classifies insurance categories based on charge levels.

Installation
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Project
Download the dataset (insurance.csv).
Open the Jupyter Notebook.
Run all cells sequentially.
Expected Output
Statistical analysis of insurance data
Visual charts and graphs
Regression model performance (R² Score)
Insurance category classification results
Future Enhancements
Add Random Forest Regression
Hyperparameter tuning
Web application deployment using Flask/Streamlit
Model performance comparison
