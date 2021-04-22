# Data Science in Finance: Credit Risk Analysis
   This is my project in DQLab courses. 

# Introduction
   Credit risk is the risk that must be borne by an individual or institution when providing loans - usually in the form of money - to other individuals or parties.
   This risk is in the form of not being able to repay the loan principal and interest, resulting in the following losses:
    *disruption of cash flow (cash flow) so that working capital is disrupted. 
    *increase operating costs to pursue these payments (collection).
   To minimize this credit risk, a process known as credit scoring and credit rating is usually carried out on the borrower.
   Many institutions use a risk rating or level of risk. The higher the rating, the higher the risk.
   
 # Decision Tree Model With Machine Learning
   The decision tree is a model structure for decision making where we follow the path from a starting point (called the root node), to the next conditions, until we reach a      conclusion.This is a suitable output model produced by analysts to help identify the risk rating. And fortunately, this model can be automatically generated from a machine learning algorithm with historical credit data input. And this has been demonstrated by an example using an algorithm called C5.0.
   
 # Class and Input Variables
![data](https://user-images.githubusercontent.com/82941103/115706931-5f0d5d80-a398-11eb-9969-e09afc145e8e.png)
Class Variables = risk_rating
Input Variables = durasi_pinjaman_bulan dan jumlah_tanggungan

# Generating a Model with the C5.0 Function
By using the dataset that we have prepared, the command to form a model and at the same time store it in one variable named risk_rating_model. 
This is the summary of the model:

![1](https://user-images.githubusercontent.com/82941103/115709513-8285d780-a39b-11eb-8ab0-98043e90aac9.JPG) 

![2](https://user-images.githubusercontent.com/82941103/115709540-8a457c00-a39b-11eb-8e2b-b24a54a7f894.JPG)

