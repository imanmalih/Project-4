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


 Split the Data into Training and Testing Sets (Already provided from kaggle CSVs)

         Create the labels set from the loan_status column, and then create the features DataFrame from the remaining columns. 


 Create a Logistic Regression Model with the Original Data

         Fit a logistic regression model by using the training data

         Evaluate the model's performance by generating a confusion matrix.


 Visualizations (Tableau)

       Use Tableau to generate visualizations. 


 Summary Analysis
 ------------------------------
Our final analysis for our Housing Loan, gives us insight on what demographic can be more directly targeted. Starting with the gender that is more likely to be approved for a loan is the male gender. 

<img width="665" alt="Screenshot 2023-11-11 at 5 12 13 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/32b6bf26-d063-40fa-8bfb-1b84523c28da">



As for the marrital status, graduate level, and self employment status, it is more likely that a married male, with a graduate degree, and that is not self-employeed has the higher chance of being accepted for the housing loan. It can be predicted that this would be the best target audience. 



<img width="613" alt="Screenshot 2023-11-11 at 5 12 23 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/57b9acdb-d3c1-439c-95ef-c9c104ccef89">

<img width="633" alt="Screenshot 2023-11-11 at 5 12 31 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/32f0e7bc-e85f-4f1b-9e96-76849f7aad5b">

<img width="665" alt="Screenshot 2023-11-11 at 5 12 36 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/c36a5e22-e831-417b-b213-233e8777d3c0">



As for the machine learning algorithim, we tested a few models and it suggests that the Logistic Regression algorithm gives us the maximum accuracy of 79%. Compared to the other 3 Machine Learning Classification Algorithms, the linear regression model fits best. We saw that the Credit History has maximum correlation with Loan Status. As expected, this tells us that the Loan Status heavily depends on the Credit History. 


<img width="995" alt="Screenshot 2023-11-11 at 5 13 02 PM" src="https://github.com/imanmalih/Project-4/assets/128860080/e50ad631-29ff-47a7-b9a1-b6f9c9a43c81">



  

  


