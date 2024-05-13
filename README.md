# Customer Churn Analysis using CRISP-DM Methodology  

## Project Overview 
---
 
![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/0c0c4289-51c2-4ddd-aa0d-e3caeed2a839)

## Business Understanding:

- Reducing the churn rate.
- Identifying key factors influencing churn, and segmenting customers based on their churn likelihood
- understanding the historical churn rates, customer demographics, products or services offered, and any existing churn prevention measures.
- Implementing the strategy to retain customers.

## Data Understanding :
The features in this dataset include the following

![Data](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/a2a1a2b8-c8db-4cf1-97f9-8369927c8bfa)


Target is Churn, which has binary classes 1 and 0. 
The objective here is to identify and quantify the factors which influence churn rate.
In below diagram it shows 74% of the customers do not churn and customer churn rate is 26%. 

![Churn](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/3b1500d8-433a-4e93-8ca8-ea651d2a0037)

# Data visualization of descriptive statistics 

## Churn with reference to gender

Here are the bar plots of demographic data of our sample. From this below demographic plots, we notice that the sample is evenly split across gender. 
With reference to churn, churn is more among males than female. There is no effect of Gender on Churn.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/45fabd95-785f-411a-8654-830764c4051c)

## Churn with reference to SeniorCitizen

In this below diagram it shows that there are only 16% of the customers who are senior citizens. Thus most of our customers in the data are younger people. Senior citizen tends to churn more

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/55fcf1de-92d4-4c69-9b4a-1c818f266dfd)

## Churn with reference to Partner

In this below diagram it shows that the sample is evenly split across partner status. About 52% of the customers have a partner.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/6f6cc92a-63c0-41e5-9db0-ade5df218a9c)

## Churn with reference to dependents 

In this below diagram it shows that only 30% of the total customers have dependents. Customer with no dependents tends to churn more.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/13e85469-b470-4444-8454-c5edcbfbeb17)

# The various offered services are plotted below.

## Churn with reference to PhoneService and MultipleLines

Multiple lines of internet connectivity doesn’t effect churn that much.

![Churn1](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/a0b3620f-e237-4770-b634-9538d4b519fe)

## Churn with reference to InternetService and Online Security

Fiber-optic internet connection is more popular than DSL internet connection and each online service has a minority of users. The Fiber optic internet is costly and thus should either be promoted to appropriate target audience or better technology can be implemented to cut cost on this service.  Ultimately the market research team has to decide the breakeven point for this service, whether it is profiting as much as the loss of customers it is causing. 

![Churn3](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/b302411a-8465-4739-8415-f08fee4cd59c)

## Churn with reference to onlineBackup and DeviceProtection

Customer opted for Online Backup churn less than who have not opted and also customers opted for Device protection churn less than who have not opted.

![Churn4](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/4d64bf41-1d6d-4289-82e8-33e8aa32325a)

## Churn with reference to TechSupport and StreamingTV

Customer opted for Tech support churn less than who have not opted and Streaming TV doesn’t make such impact on churning.

![Churn5](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/dbffef2c-6293-4efc-8090-cbd772c8f893)

## Churn with reference to StreamingMovies

Streaming Movies doesn’t make such impact on churning.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/d5506d89-4021-40a9-829c-e70111dfb1bd)

## The remaining categorical variables are related to contract and payment status.

## Churn with reference to Contract

In this below graph it is observed that most customers who are on month-to-month contracts are more likely to churn. It can be hypothesized that the reason is to be attributed to personal reasons of customers to have reservations about long term contracts or higher costs per unit time resulting from monthly contracts.

From the below graph we can see that most of the customers are in the month-to-month contract. Interestingly most of the monthly contracts last for 1-2 months, while the 2 years contracts tend to last about 70 months. This shows that customers taking a longer contract are more loyal to the company and tend to stay with it for longer time

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/19931fb1-a85f-4910-89b2-ea5ff1bb987c)

## Churn with reference to PaperlessBilling

Churn rate is higher for the customers who opted for paperless billing.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/55531542-0a6a-471d-b04f-72fe5ff55072)

## Churn with reference to PaymentMethod 

Most of the samples are on paperless billing and pay by electronic check.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/81f9a0c2-204c-48a3-ba49-9b00a3fd57fc)

## Now the distribution of the quantitative variables.

## Churn Vs Tenure

From the below histogram we can see that a lot of customers have been with the telecom company for just a month, while quite a many are there for about 72 months. This could be potentially because different customers have been different contracts. Thus, based on the contract they are into it could be more/less easy for the customers to stay/leave the telecom company.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/282d453c-5be8-43ad-bce0-b9620800281e)

## Churn Vs MonthlyCharges

It appears as if the monthly charges variable is roughly normally distributed around $80 per month with a large stack near the lowest rates. 

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/408f6960-0aab-4f8b-ae5a-b30f8d107743)

## Churn Vs TotalCharges

The total charges variable is positively skewed with a large stack near the lower amounts.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/b096b6b3-2ac6-4ac5-b76e-305ce51c52eb)

## Lastly, we will examine our main outcome variable of interest, churn.	

![churn6](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/b25c04c9-1760-41a9-8670-4cd79820afd3)

In our data, 74% of the customers do not churn. Clearly the data is skewed as we would expect a large majority of the customers to not churn. 
Now let’s explore the churn rate by tenure, seniority, contact type, monthly charges and total charges to see how it varies by these variables.

## Churn Vs Tenure:

As we can see from the below box plot, the customers who do not churn, they tend to stay for a longer tenure with the telecom company.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/7c776718-9716-4553-9b83-ffe98c70baa7)

## Churn by contract type:

The customer who has a month-to-month contract have a very high churn rate.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/04135d48-05ef-4d90-86bf-9eb587100950)

## Churn by Seniority:

Senior citizens have almost double the churn rate than younger population.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/2ec302bf-1147-4bf5-ba6d-78484294c326)

## Churn by monthly charges:

Higher percentage of customers churn when the monthly charges are high.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/d4c89991-5f49-4902-a240-3d88e12f98a3)

## Churn by total charges:

It seems that there is high churn when the total charges are lower.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/c35f2ef7-23e8-4052-bcea-bd320343eb80)

## Relation between monthly and total charges:

We are seeing from the below scatter plot that the total charges increases as the monthly bill for a customer increases.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/148bdba8-9d44-4c6e-8173-1dceacfe44e7)

# Phase3: Data Preparation:
## Data Preparation Steps:

Removing the null values (missing values) from the datase.

Converting some binary variables (Yes/No) to 0/1
 
We removed the null values from TotalCharges rows. And now the total number of observations are 7032

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/8f346f48-7eb5-4d59-af44-9f341b2c2f77)

Data after removing the null values, All the null values from the column TotalCharges got removed.

## Converting some binary variables (Yes/No) to 0/1

Converting the variables like Gender, partner, dependents, phone service, multiple lines, internet security, online security, online backup, device protection, tech support, streaming TV, streaming movies, contract, paperless billing, and payment method into binary form (0/1)

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/e44de6e7-df3b-45a6-98ba-1747ee31e510)

## Data Transformation (Data after converting the text to binary form)

# Phase4: Model Implementation
	Logistic Regression 
	Random Forest
	Tree


