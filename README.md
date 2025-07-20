# HR-Analytics-Attrition-Model

# Employee Attrition Prediction 

This project helps to find out which employees are likely to leave the company. It can help the HR team take action in advance to keep good employees.


# About the Data

The data contains details about employees, such as:

- Age, Department, Gender  
- Monthly Income, Years at Company  
- Overtime, Job Role, Work-Life Balance  
- And more...

The main column which I try to predict is `Attrition` (Yes = will leave, No = will stay).


# Tools and Libraries

I used these Python libraries:
- pandas, numpy 
- matplotlib, seaborn  
- scikit-learn


# What I Did (Step-by-Step)

1. **Looked at the data** – Checked how the data looks and if any values are missing.  
2. **Visualized** – Made graphs to understand who is leaving and why.  
3. **Cleaned the data** – Removed useless columns and converted text into numbers using Label Encoding.  
4. **Built the model** – Used a Random Forest model to predict which employees might leave.  
5. **Checked accuracy** – Used accuracy score and confusion matrix to see how good our model is.


# Graphs and Insights

I used bar plots, box plots and pairplots to find out:
- Which department has more attrition  
- Whether people who work overtime leave more  
- Age and salary differences between those who stay and those who leave  


# Model Used

 **Random Forest Classifier** from scikit-learn

This model works like a smart group of decision trees to make predictions.




