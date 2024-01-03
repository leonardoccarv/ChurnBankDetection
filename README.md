# ChurnBankDetection
- DATA: https://kaggle.com/datasets/sakshigoyal7/credit-card-customers
- A bank manager is in a scenario where several customers are leaving their credit card services. It would be extremely interesting for the company to be able to predict the customers most likely to leave such services so that, in this way, the bank can act preventively in order to offer better services in favor of maintaining the customer. The data set has 10,000 customers with attributes such as age, salary, marital status, credit limit, card category, among others. There are approximately 18 features in the whole set and there are only 16.0% of customers with churn.
# Features
- **CLIENTNUM:** unique identifier of the customer cartonista;
- **Attrition_Flag:** internal event related to customer activity;
- **Customer_Age:** age of the customer (in years);
- **Gender:** gender of the client (M = Male, F = Female);
- **Dependent_coun:** number of customer dependents;
- **Education_Level:** customer's school level;
- **Marital_Status:** marital status of the client;
- **Income_Category:** category related to the client's annual salary;
- **Card_Category:** credit card category (Blue, Silver, Gold or Platinum);
- **Months_on_book:** period of relationship with the bank (in months)
- **Total_Relationship_Count:** indicator of the customer's general relationship with the bank;
- **Months_Inactive_12_mon:** number of months of customer inactivity considering the last 12 months;
- **Contacts_Count_12_mon:** number of contacts registered by the customer considering the last 12 months;
- **Credit_Limit:** customer's credit limit;
- **Total_Revolving_Bal:** total revolving balance on the credit card;
- **Avg_Open_To_Buy:** indicator of purchase willingness by the customer (opening of offer);
- **Total_Amt_Chng_Q4_Q1:** probably indicates the value migrated between Q4 and Q1 for a full annual period;
- **Total_Trans_Amt:** total transaction amount (l|ast 12 months);
- **Total_Trans_Ct:** total transaction count (last 12 months);
- **Total_Ct_Chng_Q4_Q1:** probably indicates the amount migrated from card transactions between Q4 and Q1 for a full annual period;
- **Avg_Utilization_Ratio:** indicator of average customer usage of the card;
- **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_Mon_Dependent_Count_Education_Level_Months_Inactive_12_Mon_1:**
- **Naive_Bayes_Classifier_Attrition_Flag_Card_Category_contacts_Count_12_Mon_Dependent_Count_Education_Level_Months_Inactive_12_Mon_2:**
## Problem Solution
- Build a model that determines potential customers to churn.
# Conclusion and next steps
- With this model we obtain an result of 93% for predicting churn for a bank customer. Now, the next steps would be to create benefits with the aim of retaining customers who are likely to churn.
