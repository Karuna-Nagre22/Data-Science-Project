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
- Logistic Regression 
- Random Forest
- Tree

After going through the above EDA (Exploratory Data Analysis) we will develop some predictive models and compare them. We will develop Logistic Regression and Random Forest.
It is important to scale the variables in logistic regression so that all of them are within a range of 0 to 1. Before model implementation we split the data into training and test sets (70% vs 30%)

## Cross validation:

For any model in machine learning this considered as a best practice if the model is tested with the independent data-set.  Normally any prediction model work on unknown dataset which is also known as training set. It is fit to work with any model in the future. It helps us better use our data and it gives us much more information about our algorithm performance.   
Since our data is imbalanced dataset the cross validation process with 10 folds is carried out. Data Sampler widget selects a subset of data instances from an input dataset. 

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/3fe23b3e-59e5-43f5-9143-129da3c5924b)

## Train Test splitting by using Data Sampler widget.
In Data sampler we are dividing the data into 70, 30 ratio and cross validation as 10

Train a training set.
Validating a validation set (eg. using k-fold cross validation)
Testing the model with a test set.
This below figure shows that the 70% of the data which is 4931 records are into training set.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/0b340a7e-39ff-4ba4-94bf-56cb357faddc)

And the remaining data that is 30% (2112) records are into test set.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/77619ba6-01a6-459f-91c6-24efcec56e08)

## Logistic Regression:

Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes. 
In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).

## Random Forest:

Random forest is a supervised learning algorithm which is used for both classification as well as regression. But however, it is mainly used for classification problems. 
As we know that a forest is made up of trees and more trees means more robust forest. 
Similarly Random Forest algorithm creates decision trees on data samples and gets the prediction from each of them and finally selects the best solution by means of voting. 
It is assembled method which is better than a single decision tree because it reduces the over-fitting by averaging the result. 

## Working of Random Forest Algorithm

We can understand the working of Random Forest algorithm with the help of following steps
Step1- First, start with the selection of random samples from a given dataset.
Step2- Next, this algorithm will construct a decision tree for every sample. Then it will get the prediction result from every decision tree.
Step3- In this step, voting will be performed for every predicted result.

## The following diagram will illustrate its working-

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/d875b7f3-c63c-4280-8018-1cf68a985b1b)

## Tree:

Tree is a simple algorithm that splits the data into nodes by class purity. It is a precursor to Random Forest. Tree in Orange is designed in-house and handle both discrete and continuous datasets. It can also be used for both classification and regression tasks.

### Tree parameters:
- Induce binary tree: build a binary tree (split into two child nodes).
- Min. number of instances in leaves: if checked, the algorithm will never construct a split which would put less than the specified number of training examples into any of the branches.
- Do not split subsets smaller than: forbids the algorithm to split the nodes with less than the given number of instances.
- Limit the maximal tree depth: limits the depth of the classification tree to the specified number of node levels.

## Training The Models 

Data is getting trained through the models (Logistic Regression, Random Forest, and Tree) and making the predictions for the test data.

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/9fa8c4c0-4b69-4f97-b0dd-623f5b0d4728)

# Phase 5: Evaluation (Model in terms of accuracy)

## Evaluation results for Training Data:

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/7bc548fa-7e65-41ad-836e-2c363e26edd0)

The logistic regression model work better than the other two models random forest and Tree model.  For the training set, the accuracies are 0.75 for Tree, 0.79 for Random Forest and 0.80 for Logistic Regression.

## Evaluation Results for Test Data:

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/80d9a306-f362-49f4-ab01-c5bbde177be6)

The logistic regression model work better than the other two models random forest and Tree model. For the test set, the accuracies are 0.75 for Tree, 0.79 for Random Forest and 0.80 for Logistic Regression.

## Confusion Matrix:

The confusion matrix is a matrix used to determine the performance of the classification models for a given set of test data. It can only be determined if the true values for test data are known.  Since it shows the errors in the model performance in the form of a matrix, hence also known as an error matrix.

## Some features of Confusion matrix are:

For the 2 prediction classes of classifiers, the matrix is of 2*2 table.
The matrix is divided into two dimensions, that are predicted values and actual values along with the total number of predictions.
Predicted values are those values, which are predicted by the model, and actual values are the true values for the given observations.

True Negative: Model has given prediction No, and the real or actual value was also No.

True Positive: The model has predicted yes, and the actual value was also true.

False Negative: The model has predicted no, but the actual value was Yes, it is also called as Type-II error.

False Positive: The model has predicted Yes, but the actual value was No. It is also called a Type-I error.

## Accuracy:

The accuracy is the measurement of how many cases the model has correctly identified. It is one of the important parameters to determine the accuracy of the classification problems. It defines how often the model predicts the correct output. It can be calculated as the ratio of the number of correct predictions made by the classifier to all number of predictions made by the classifiers.

**Accuracy** = TP+TN/TP+FP+FN+TN

## Precision:

It can be defined as the number of correct outputs provided by the model or out of all positive classes that have predicted correctly by the model, how many of them were actually true. It can be calculated as:

Precision=TP/TP+FP

## Recall: 

It is defined as the out of total positive classes, how our model predicted correctly. The recall must be as high as possible.

Recall=TF/TP+FN

## F-measure:

If two models have low precision and high recall or vice versa, it is difficult to compare these models. So, for this purpose, we can use F-score. This score helps us to evaluate the recall and precision at the same time. The F-score is maximum if the recall is equal to the precision.

The F1 score is the harmonic mean of the precision and recall. The higher F1 score is, the better performance of the model (best value is at 1 — perfect precision and recall)

F-score= 2*Recall*Precision/Recall+Precision.

## Sensitivity:

Sensitivity measures the proportion of actual positive cases that are correctly captured by the model

Sensitivity = TP/TP+TN

## Specificity:

Specificity measures the ability to detect the actual negative cases correctly.

Specificity=TN/TN+FP

# Implementation of confusion matrix and ROC analysis for Train Test Data:  

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/e6cc7a2a-5745-435e-9a3b-708cf6045e0d)

## Confusion matric for Logistic Regression of Training Dataset

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/4d82b8db-89ff-47ed-aa39-c61dfa7e7afc)

There are actual and predicted values . It has been taken 4931 records for Training set.

True Positive (TP) = 3217 (These are cases in which we predict yes (they churned), and they did churn.

True Negative(TN) = 748 (We predicted no, and they didn’t churn).

False Positive(FP) = 384 (We predicted yes, but they didn’t actually churn, also known as Type I error) 

False Negative(FN) = 582 (We predicted no, but they actually churned, also known as Type II error)

## Confusion matric for Logistic Regression of Test Dataset

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/38bb6ce1-da6d-49ed-938b-07d500d64a63)

There are actual and predicted values.  It has been taken 2112 records for Training set.

True Positive (TP) = 1408 (These are cases in which we predict yes (they churned), and they did churn.

True Negative(TN) = 261 (We predicted no, and they didn’t churn).

False Negative(FP) = 165 (We predicted yes, but they didn’t actually churn, also known as Type I error)

False Positive(FN) = 278 (We predicted no, but they actually churned, also known as Type II error)

## ROC Curve:

A receiver operating characteristic curve, or ROC curve is a graphical plot that illustrates the diagnostic ability of a binary classifier system as its discrimination threshold is varied. 
ROC curve is a two-dimensional graph in which the false positive rate(specificity) is plotted on the x-axis and the true positive rate (1-sensitivity) is plotted no the y-axis. 
The ROC curves are useful to visualize and compare the performance of classifier methods.
The closer the curve follows the left-hand border and then the top border of the ROC space, the more accurate the classifier.

## ROC of the training dataset for all the models 

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/47769a5f-38d2-40d3-a876-cf6baec27219)

This ROC curve is constructed by plotting the sensitivity against 1-specificity for each possible cut-off. The maximum values on x-axis and y-axis is 0 to 1. These are probability. So, the area is equal to 1.
The diagonal connects from origin to other outer edge of the square. This diagonal divides the square exactly into two parts that is 0.5 and 0.5 
Anything above 0.5 is the value addition that we are doing to this analysis. More the region better the model it is. 
The ROC (Receiver Operating Characteristic) Curve is a relationship between True Positive Rate and False Positive Rate. Logistic Regression, which is the red line, has an area of 0.849 under the curve. It means the model has performed better. 
The AUC of this model is between 0.5 and 1 
AUC ROC-curve of Logistic Regression = 0.849
AUC ROC-curve of Random Forest = 0.820
AUC ROC-curve of Tree = 0.629
We see that the model Logistic Regression leads to higher AUC and should be preferred over Models Tree and Random Forest.

## ROC of the test dataset for all the models 

![image](https://github.com/Karuna-Nagre22/Data-Science-Project/assets/169028009/dcde14ea-15a2-4214-a7be-adb32c3242ca)

The AUC of this model is between 0.5 and 1 
AUC ROC-curve of Logistic Regression = 0.833
AUC ROC-curve of Random Forest = 0.796
AUC ROC-curve of Tree = 0.596
We see that the model Logistic Regression which is (red line) leads to higher AUC and should be preferred over Models Tree and Random Forest.

## Conclusion

Telecommunication industry always suffers from a very high churn rates when one industry offers a better plan than the previous there is a high possibility of the customer churning from the present due to a better plan in such a scenario it is very difficult to avoid losses but through prediction we can keep it to a minimal level. 

We identified several important churn predictor variables from these models and compared these models on accuracy measures.

Customers with month-to-month contracts are less likely to churn.

Customers with internet service, in particular fiber optic service, are more likely to churn.

Customers who have been with the company longer or have paid more in total are less likely to churn.

The Logistic Regression is found to be the best predictive model with good accuracy compared to other models for the data set taken.

Logistic Regression model helps to identity the probable churn customers and then make the necessary business decisions.

