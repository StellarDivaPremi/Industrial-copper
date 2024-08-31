# Industrial-copper
Guvi project for Industrial copper selling price and status prediction


# **Industrial Copper Modeling**

## **Project Overview**

This project aims to develop machine learning models to address key challenges in the copper industry, such as predicting the selling price of copper and classifying leads based on their likelihood to convert into customers. The project focuses on handling issues like skewness, noisy data, and optimizing pricing decisions using regression and classification models.

### **Skills Gained from This Project**
- Python scripting
- Data Preprocessing and Exploratory Data Analysis (EDA)
- Streamlit application development
- Machine Learning modeling for regression and classification

### **Domain**
- Manufacturing

## **Problem Statement**

The copper industry faces challenges with sales data that may suffer from skewness and noise, affecting the accuracy of manual predictions. This project leverages machine learning models for regression and classification to improve data-driven decision-making. The goal is to predict continuous variables like selling prices and classify leads as "WON" or "LOST."

### **Key Objectives:**
1. Explore skewness and outliers in the dataset.
2. Transform and preprocess data for machine learning.
3. Develop a regression model to predict the selling price.
4. Build a classification model to predict lead status ("WON" or "LOST").
5. Create a Streamlit web application for real-time predictions.

## **Data Description**

The dataset contains various features related to copper sales, including:

1. **id**: Unique identifier for each transaction.
2. **item_date**: Date of the transaction.
3. **quantity tons**: Quantity of the item in tons.
4. **customer**: Identifier for the customer.
5. **country**: Country of the customer.
6. **status**: Status of the transaction (e.g., "WON", "LOST").
7. **item type**: Type or category of the item.
8. **application**: Specific use or application of the items.
9. **thickness**: Thickness of the items.
10. **width**: Width of the items.
11. **material_ref**: Reference for the material used.
12. **product_ref**: Reference for the specific product.
13. **delivery date**: Expected or actual delivery date.
14. **selling_price**: Price at which the items are sold.

## **Approach**

1. **Data Understanding:**
   - Identify types of variables (continuous, categorical).
   - Handle missing values, outliers, and skewness.
   - Encode categorical variables using suitable techniques.

2. **Data Preprocessing:**
   - Handle missing values using mean/median/mode.
   - Treat outliers using IQR or Isolation Forest.
   - Transform skewed data using log or boxcox transformations.

3. **Exploratory Data Analysis (EDA):**
   - Visualize data distribution and relationships using Seaborn's plots.
   - Identify important features using correlation matrices.

4. **Model Building:**
   - **Regression Model**: Predict continuous variable "Selling_Price".
   - **Classification Model**: Predict lead status ("WON" or "LOST").
   - Optimize models using cross-validation and grid search.

5. **Model Deployment:**
   - Create an interactive web application using Streamlit for real-time predictions.

## **Data Preparation and Feature Engineering**

- Handle skewness and outliers.
- Encode categorical variables.
- Feature selection and engineering to create more informative data representations.
- Split data into training and testing sets.

## **Model Development and Evaluation**

- Train and evaluate different models like ExtraTreesClassifier, XGBClassifier, and Logistic Regression.
- Use metrics like accuracy, precision, recall, F1 score, and AUC for evaluation.
- Optimize models using cross-validation and grid search.

## **Deployment with Streamlit**

Develop a user-friendly interface using Streamlit that allows:
1. Selection of the task (Regression or Classification).
2. Input fields for all relevant features except the target variable.
3. Display of the predicted selling price or lead status based on user input.

## **Learning Outcomes**

- Proficiency in Python for data analysis and machine learning.
- Experience with data preprocessing techniques and EDA.
- Understanding machine learning concepts for regression and classification.
- Developing and deploying a web application using Streamlit.
- Practical skills in solving real-world problems in the manufacturing domain.

## **Project Evaluation Metrics**

- Write code in a modular and maintainable manner.
- Ensure the code is portable and follows Python coding standards (PEP 8).
- Maintain a public GitHub repository with a well-documented README file.
- Provide a demo video on LinkedIn demonstrating the working model.

## **Tools and Technologies**

- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit
- Data Analytics: Power BI, Tableau
- Machine Learning Algorithms: ExtraTreesClassifier, XGBClassifier, Logistic Regression
- Deployment: Streamlit Web Application

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/industrial-copper-modeling.git
   ```
2. Navigate to the project directory:
   ```bash
   cd industrial-copper-modeling
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

