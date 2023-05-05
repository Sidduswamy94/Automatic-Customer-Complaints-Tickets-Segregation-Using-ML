# Automatic-Customer-Complaints-Tickets-Segregation-Using-ML
Automatic Customer Complaints Tickets Segregation or Classification Using Machine Learning

<b> In this article, I am using Finance Company dataset as "Finance_data.json".

<b> In this article, we are going to Automatic Customer Complaints Tickets Segregation or Classification Using Machine Learning, based on information given by the customers.

## Business Problem Understanding
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, we will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.

We need to build a model that is able to classify customer complaints based on the products/services. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.
With the help of topic modelling, we will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, we will be able to identify the topics of the customer complaints.

We will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, we need to apply techniques to analyze patterns and classify tickets into the following five clusters based on their products/services:

1. Credit card / Prepaid card


2. Bank account services


3. Theft/Dispute reporting


4. Mortgages/loans


5. Others

With the help of topic modelling, we will be able to map each ticket onto its respective department/category. We can then use this data to train any supervised model such as logistic regression, decision tree, random forest and Naive Bayes Algorithm. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.


### Pipelines that needs to be performed:
We need to perform the following eight major tasks to complete the case-study:

1. Data loading


2. Text preprocessing


3. Exploratory data analysis (EDA)


4. Feature extraction


5. Topic modelling 


6. Model building using supervised learning


7. Model training and evaluation


8. Model inference
