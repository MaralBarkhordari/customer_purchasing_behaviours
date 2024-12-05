### **Customer Purchasing Behaviours** - Team Project

## **Team Members :** </br>
Anshu Dwivedi </br>
Henry Giorgi </br>
Maral Barkhordari </br>
Sonu Abraham </br>
Keyuan Huang

## **Business case** : </br>
Use predictive analytics to recommend the most effective marketing strategies for different customer segments based on their purchasing frequency, loyalty score, and annual income.</br>

Our team has chosen the **Customer Purchasing Behavior Dataset** for in-depth analysis, aiming to derive valuable insights into customer purchasing behaviors. </br>

The objective of this project is to understand how various features correlate to determine the effective marketing strategies. By utilizing regression model, we aim to predict marketing strategies that adddress the diverse interests of various customer segments.This analysis will leverage details from the dataset including customer age, annual income, region,loyalty score and purchashing frequency.

## **About Dataset:**</br>
**customer_id**: Unique ID of the customer.</br>
**age**: The age of the customer.</br>
**annual_income**: The customer's annual income (in USD).</br>
**purchase_amount**: The total amount of purchases made by the customer (in USD).</br>
**purchase_frequency**: Frequency of customer purchases (number of times per year).</br>
**region**: The region where the customer lives (North, South, East, West).</br>
**loyalty_score**: Customer's loyalty score (a value between 0-100).</br>

## Our Approach </br>

Step 1: **Data Understanding and Preprocessing** </br>

 We loaded, cleaned, and preprocessed the dataset, addressing missing values and outliers, and scaled numerical features and encoded categorical variables.

Step 2: **Exploratory Data Analysis (EDA):** </br>

We conducted segmentation analysis based on customer income and loyalty scores, visualizing purchasing behaviors through histograms, scatter plots, and box plots to identify patterns.

Step 3: **Model Selection and Training** </br>

We compared different models, including Linear Regression, Decision Tree, and Random Forest. Random Forest emerged as the most effective model due to its high performance and feature importance.

Step 4: **Model Evaluation**</br>

We evaluated model performance using R², MAE, and RMSE, and fine-tuned the Random Forest model with GridSearchCV to optimize hyperparameters.

Step 5: **Interpretation and Insights**</br>

- The most infleuntial features that significantly affect customer purchasing behavior are annual_income, loyalty_score and purchase_to_income_ratio.

- Customer Segments with :
  
    - High Income, Low loyalty score : Offer premium rewards and exclusive services to build loyalty that can help to increase retention.

    - Low Income, High Loyalty: Provide small, frequent rewards and discounts to retain engagement.

    - Medium Income, Moderate Loyalty: These are average earners with moderate engagement. Use value-driven promotions like bundles and seasonal offers to boost frequency.

- Key Visual Insights :
  
    - Income Vs Loyalty(Box Plot): High-income customers often have untapped engagement potential.

       ![image](https://github.com/user-attachments/assets/96f0cef3-50a9-4141-aad5-997bd1972b47)

    - Loyalty Score Vs Purchasing Frequency : Loyalty increases align with higher purchasing frequency, highlighting opportunities for tiered programs.

       ![image](https://github.com/user-attachments/assets/40e44bef-7461-4de5-af0a-0842616eccec)

    - Segmented Bar Plot: Loyalty and income directly influence purchasing frequency, suggesting tailored strategies for each combination.

    - Violin Plot (Loyalty Score): Loyalty score distributions vary with purchasing frequency, offering clues about engagement levels across different groups.
      
       ![image](https://github.com/user-attachments/assets/f92d50c0-ff07-4e41-a5cc-791c84c4b041)

    - 3D Scatter Plot : Visualizes interactions between income, loyalty, and purchasing frequency, revealing distinct customer clusters for strategic targeting.

       ![image](https://github.com/user-attachments/assets/6d674a8b-5f52-4163-986c-1280e1d92d66)


    **Videos:**</br>
    
    Sonu Abraham - https://drive.google.com/file/d/1F4KytKKsRCrrS-Qu_vtHZOqePTLyBkyt/view?usp=drive_link
    
    Anshu Dwivedi -
    
    Henry Giorgi -
    
    Maral Barkhordari -
    
    Keyuan Huang -

