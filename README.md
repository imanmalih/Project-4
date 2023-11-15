# Project-4


## Contributors: 
     Iman Malih, 
     Hayden Jackson, 
     A'Nayah Mccollough, 
     John Olton, 
     Ryan Woyce, 
     Qonesha Hunter
 
**Project Overview**
--------------------------------
The company wants to automate the loan eligibility process based on customer detail provided while filling the online application form. 
Construct a Machine Learning model to predict a person's eligibility of loan approval based on some information about that person. 


Datasets to be Used:

https://www.kaggle.com/datasets/vikasukani/loan-eligible-dataset/data

*Breakdown of Tasks:*
---------------------------------

Data Prepartion and Analysis

    Load and Explore the Datasets:

          Use Python Pandas to load the datasets.

          Explore the data, understand the columns and identify key features for analysis.


 Split the Data into Training and Testing Sets 

         Create the labels set from the loan_status column, and then create the features DataFrame from the remaining columns. 


 Create Prediction Models with the split data

         Evaluate each model's performance by generating a confusion matrix.


 Visualizations (Python)

      


 Summary Analysis
 ------------------------------
Our final analysis for our Housing Loan, gives us insight on what demographic can be more directly targeted. Starting with the gender that is more likely to be approved for a loan is the male gender. 

![image](https://github.com/imanmalih/Project-4/assets/133404805/68de3a63-004a-49b7-925b-e18bb103bd54)




As for the marrital status, graduate level, and self employment status, it is more likely that a married male, with a graduate degree, and that is not self-employeed has the higher chance of being accepted for the housing loan. It can be predicted that this would be the best target audience. 



![image](https://github.com/imanmalih/Project-4/assets/133404805/c9fd65e7-ca3c-4ac8-840e-ebae222d7f28)


![image](https://github.com/imanmalih/Project-4/assets/133404805/d7323010-47cf-40c8-8b94-156e968a6f9f)


![image](https://github.com/imanmalih/Project-4/assets/133404805/6b000423-f94b-405b-8655-be10e57dc152)


<img width="995" alt="Screenshot 2023-11-11 at 5 13 02 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/e50ad631-29ff-47a7-b9a1-b6f9c9a43c81">

From our correlation matrix (pictured above) we saw that the Credit History has maximum correlation with Loan Status. 
As expected, this tells us that the Loan Status heavily depends on the Credit History. 



Conclusion
 ------------------------------

As for the machine learning algorithim, we tested a few models such as Logisitic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors and it suggests that the Logistic Regression algorithm gives us the maximum accuracy of 79%. Compared to the other 3 Machine Learning Classification Algorithms, the logistic regression model fits best overall. 


  


