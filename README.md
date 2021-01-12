---
categories: 
- machine learning
date: "2020-01-12"
slug: predict-churning-customers
tags: []
title: Predict Churning Customers
---

# Final Project of Data Mining Course - Big Data Analysis

A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction

This dataset is from a website with the URL as https://leaps.analyttica.com/home. Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

From this data set we can predict the customers who are going to stop using credit cards. Using this model/result, the company can make offer to employess to retain them.

## Attribute Information

* **CLIENTNUM**                : Client number. Unique identifier for the customer holding the account
* **Attrition_Flag**           : Internal event (customer activity) variable - if the account is closed then 1 else 0
* **Customer_Age**             : Customer's Age in Years
* **Gender**                   : M=Male, F=Female
* **Dependent_count**          : Number of dependents
* **Education_Leel**           : Educational Qualification of the account holder (example: high school, college graduate, etc.)
* **Marital_status**           : Married, Single, Divorced, Unknown
* **Income _Category**         : Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, >
* **Card_Category**            : Product Variable - Type of Card (Blue, Silver, Gold, Platinum)
* **Months_On_Book**           : Period of relationship with bank
* **Total_Relationship_Count** : Total no. of products held by the customer
* **Months_Inactive_12_mon**   : No. of months inactive in the last 12 months
* **Contacts_Count_12_mon**    : No. of Contacts in the last 12 months
* **Credit_Limit**             : Credit Limit on the Credit Card                                                                                                           
* **Total_Revolving_Bal**      : Total Revolving Balance on the Credit Card
* **Avg_Open_To_Buy**          : Open to Buy Credit Line (Average of last 12 months)
* **Total_Amt_Chng_Q4_Q1**     : Change in Transaction Amount (Q4 over Q1)
* **Total_Trans_Amt**          : Total Transaction Amount (Last 12 months)
* **Total_Trans_Ct**           : Total Transaction Count (Last 12 months)
* **Total_Ct_Chng_Q4_Q1**      : Change in Transaction Count (Q4 over Q1)
* **Avg_Utilization_Ratio**    : Average Card Utilization Ratio
