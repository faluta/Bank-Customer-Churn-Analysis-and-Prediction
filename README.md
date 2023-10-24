# Bank Customer Churn Analysis and Prediction
## by Faluta Opeyemi

## Important Note
This analysis was done using Jupyterlite notebook and as such would require you to modify the codes by removing piplite wherever it surfaces. 
Also, the GUI section of this project will not run using the Jupyterlite notebook. This section must be ran on the notebook on your local computer as opposed to the online version called Jupyterlite 

## Dataset

> In business context, it is important to identify and understand the leading factors of churn among customers. It is a well known fact that it is easier and less costlier to keep existing customer than source for new ones.   
As such, it is important for businesses to retain customers while staying competitive and profitable.   



The data set contains information valuable to predict a bank's churn rate. The data contains 10000 records and 18 columns.

A breif description of each column is described below:

1.  <b> RowNumber </b> — corresponds to the record (row) number and has no effect on the output.   
2.  <b> CustomerId </b> — contains random values and has no effect on customer leaving the bank.  
3.  <b> Surname </b> — the surname of a customer has no impact on their decision to leave the bank.  
4.  <b> CreditScore </b> — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.  
5.  <b> Geography </b> — a customer’s location can affect their decision to leave the bank.  
6.  <b> Gender </b> — it’s interesting to explore whether gender plays a role in a customer leaving the bank.  
7.  <b> Age </b> — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.  
8.  <b> Tenure </b> — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.  
9.  <b> Balance </b> — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.  
10. <b> NumOfProducts </b> — refers to the number of products that a customer has purchased through the bank.  
11. <b> HasCrCard </b> — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.  
12. <b> IsActiveMember </b> — active customers are less likely to leave the bank.  
13. <b> EstimatedSalary </b> — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.  
14. <b> Exited </b> — This is the target variable and it shows whether or not the customer left the bank.    
15. <b> Complain </b> — customer has complaint or not.  
16. <b> Satisfaction Score </b> — Score provided by the customer for their complaint resolution.  
17. <b> Card Type </b> — type of card hold by the customer.  
18. <b> Points Earned </b> — points earned through various loyalty or rewards programs including credit card usage and other banking products or services. 

## Summary of Findings

i.    The Bank has a moderately young age distribution with adults (26-40) and young adults (18-25) making up a total of 64% of the Bank's customer base population.

ii    The Bank approximately has 20% churn rate with middle age adults (41-60) accounting for the majority of the  Bank's churn.

iii.  Customers with a one-year tenure have the highest churn rate (23%). It is recommended that the Bank strengthens its onboarding programmes for new clients and measure the effectiveness.

iv.   Analysis shows that customers with 2 bank products churn the lowest (8%) with higher amounts of product resulting to a 80-100% churn rate. To counter the effect, the bank should review/strengthen its product offering, incentivize bundle product packages, provide personalised product services and measure its effectiveness.

v.    Germany has the highest churn rate by geography (32%); The Bank needs to understand the common complaints amongst their customers in Germany and replicate the customer experience and customer success initiatives done in France and Spain.  

vi.   Analysis shows that the average account balance of a customer reduces as the number of products increases. The impact is more pronounced on retained customers than their churned counterpart.  

vii.  An active customer is less likely to churn.  

viii. Retained customers have a relatively higher credit score than their churned counterpart. 

ix.   Based on the filtering criteria, 1176 customers qualify and should be advised to own a credit card as they are potentially at risk to churn. 

x.    Further investigation can be carried out on 337 churned customers who qualified but did not own a credit card. This will help the Bank identify factors that determines churn. 

xi.   The Bank needs to improve its satisfaction score across board as the average satisfaction score shows that customers are neutral (3).

## Recommendations

i.   Customer Onboarding: A recommended course of action is for the Bank to strengthen its onboarding programmes for new clients and measure the effectiveness on customer retention. 

ii.  Offer Personalized Products: In addition to having a great customer onboarding, the Bank should review or strengthen their personalized products, incentivize bundle packages and services that better meet the needs of different customer segments. 

iii. Informative Newsletters: Based on the analysed data, it is important for the Bank to disseminate information to customers in an educative format through newsletters.Insights can be shared on spending habits, optimized credit card usage and ways to boost credit scores and the dangers of utilizing a high number of Banking products without fully understanding the product.  

iv.  Know Your Customer (KYC): The bank can improve their customer profiling and segmentation prediction which would boost the performance/success of the recommended personalized product for the targeted customer KYC is also useful for customer relationship management and credit risk assessment.  

v.   Proactive Credit Card Offerings: Based on the analysed data, there are customers who qualify to own a credit card based on their credit score and points earned.The Bank needs to be proactive by recommending their competitive credit card offerings to the qualified customers. The success of this recommendation should prove effective if the advantages of customer profiling is leveraged appropriately.  

vi.  Demographics Matter: It is important to take into identify the differences amongst various demographics. Whether it is the culture, spending habits or credit utilization among other factors. They all comes into play when considering customer experience, customer satisfaction and
product offerings.  

v.   Continuous Improvement: Continuous improvement and actively acting on customers’ feedback cannot be overemphasized.This will prove useful in improving the Bank’s customer satisfaction score if implemented correctly.  

vi. What Matters: Based on the analysed data, the “Number of products” purchased by the customer has the most significant effect on customer churn. Other important features were credit card ownership and account balance. It is important for the Bank to pay attention to these features.
