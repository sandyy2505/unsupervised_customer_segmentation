# Customer_segmentation with K-Means & Hierarchical clustering
Unsupervised clustering technique - K-Means &amp; Hierarchical clustering

# Context:
AllLife Bank wants to focus on its credit card customer base in the next financial year. They have been advised by their marketing research team, that the penetration in the market can be improved. Based on this input, the Marketing team proposes to run personalised campaigns to target new customers as well as upsell to existing customers. Another insight from the market research was that the customers perceive the support services of the back poorly. Based on this, the Operations team wants to upgrade the service delivery model, to ensure that customers queries are resolved faster. Head of Marketing and Head of Delivery both decide to reach out to the Data Science team for help

# Objective
To identify different segments in the existing customer based on their spending patterns as well as past interaction with the bank.

# Dataset:
Data Description: Data is of various customers of a bank with their credit limit, the total number of credit cards the customer has, and different channels through which customer has contacted the bank for any queries, different channels include visiting the bank, online and through a call centre.

* Sl_no: Serial number
* Customer key: Identifier for the customer
* Average Credit Limit: Average credit limit across all the credit cards
* Total credit cards: Total number of credit cards
* Total visits bank: Total number of bank visits
* Total visits online: Total number of online visits
* Total calls made: Total number of calls made by the customer

# Key Questions:
1. Perform EDA.
2. Apply Clustering Algorithms and mentions how many clusters are formed ?
3. How are these segments different from each other?
4. What are your recommendations to the bank on how to better market to and service these customers?

# Analysis of clusters and questions answered :
#### 1. How many different segments of customers are there? 
Answer : Total numbers of segments are 3

#### 2. How are these segments different from each other? (Cluster profiles )
Answer: 
**Label 0 can be considered low valued customers**
   
    This group comprises of about 34% of the customers ( 224/660 )
    
    These customers have a mean "Avg_Credit_Limit " around 12200 and have 2 credit card on an average and the maximum number of credit card as 4.
    
    They are the ones who makes the most number of customer care calls to the bank as the average calls made is 7 


**Label 1 can be considered medium valued customers** 
    
    This group forms the majority of the customers having about 58% customers in total  ( 386/660 )
    
    These customers have  "Avg_Credit_Limit " ranging from 5000.0 to 100000.0 
    
    These are the ones which make the maximum number of visits to the bank as the average visits to bank is 3.
    
    They are the ones who are least active online as the maximum visit onine is just 3



**Label 2 can be considered  high value customers** 
    
    These are the least in number i.e. only 50 customers comprising 7.5% of total customers (50/660) .
    
    These customers have a minimum "Avg_Credit_Limit " of 84000 and have atleast 5 Credit cards .
    
    These are the ones which make the minimum number of visits to the bank as the maximum visit to bank is 1 amongst all 50     customers.
    
    They are mostly using online services as the average visit online is 11.

#### 3. What are your recommendations to the bank on how to better market to and service these customers? (Business Recommendations )
1. Customers in the medium group ( having Label 1 ) are not engaged much in online activities , one of the exercise can be to engage them online. If they join online , promotions and offers can be communicated to them with much ease.
2. Customers in low group ( label 0 ) can further be binned to check if there are any extreme groups having high average credit limit.These customers can be given more offers and new credit cards so that we can have them in medium group (label 1 )  over a period of time. Similarly we can perform this for medium customers (label 1)  and try to have them in high group (label 2) over a period of time .
3. Customers in low group ( label 0 ) make the most number of customer care calls, these customers can be told about different offers to try and move them to  medium group over a period of time .

