<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Customized Offers - retail of car insurances to your customer
*Linda Ritter | Data Analyst*

*Data Squad 21, Lisbon 02.10.2019*

## Content
- [Project Description](#project-description)
- [Product](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
How can you increase, as a car insurance company, the conversion rate of accepted offers? 
- By automatization of customized offers!

Increasing the conversion rate is the beginning of a great journey to make your company much more effective and lean, these are the main factors to promise a great growth. I will help you by inventing the robo adviser and if you want - much more!
The way to scale up your business is to build a lean business strategy by focusing only on those customers who really need your insurance, making them happy and feel safe buying your product. Get rid of unnecessary financial drains that hinder your growth.
For this implement my robo adviser.

<a name="hypotheses-/-questions"></a>

## Product

Your way to increase your conversion rate:

#### ANALYSE
Know your customer and his/her needs!

#### CUSTOMIZE
Offer customized car insurances to your client

#### AUTOMATIZE
Everything done by the robo adviser


The robo adviser will analyse your customers and his/her needs. It searchs for the best offer and will send only customized offers to those clients who want a car insurance. Thereby you will increase your conversion rate up to 89%. The key in this matter is focusing on your target group, get rid of customers who are not interested in your product and put all your effort in those clients which need your insurance!

<a name="dataset"></a>

## Dataset
[Kaggle | IBM Watson Marketing Customer Value Data](https://www.kaggle.com/pankajjsh06/ibm-watson-marketing-customer-value-data)

<a name="workflow"></a>

## Workflow

##### Exploratory Data Analysis 
9,134 rows
23 features ('Customer', 'State', 'Customer Lifetime Value', 'Response', 'Coverage','Education', 'Effective To Date',   'EmploymentStatus', 'Gender','Income', 'Location Code', 'Marital Status', 'Monthly Premium Auto','Months Since Last Claim', 'Months Since Policy Inception','Number of Open Complaints', 'Number of Policies', 'Policy Type','Policy', 'Renew Offer Type', 'Sales Channel', 'Total Claim Amount','Vehicle Class', 'Vehicle Size')
label = Response (Yes/No)
Categorical Types
Imbalanced Dataset
Supervised Machine Learning
Classification

##### Data Analysis
Categorical data to numerical data
Imbalanced dataset: Downsampling

##### Supervised Machinelearning
Tested models: K-nearest neighbor, LogisticRegression, Decission Tree

###### Decission Tree:
Accuracy Score: 88.67%
The accuracy score for the training data is:  90.45 %
The accuracy score for the test data is:  88.67 %
--> no Overfitting

cross validation score (5): 91.55 %, 90.78 %, 88.83 %, 91.50 %, 92.72 %

Recall_score: 97.83 %

Precision_score: 57.42 %

<a name="organization"></a>

## Organization
For organization I used Trello.

<a name="links"></a>

## Links

[Repository](https://github.com/LindaRit/Project-Week-4/edit/master/your-project) 

[Source | Kaggle](https://www.kaggle.com/pankajjsh06/ibm-watson-marketing-customer-value-data)  

[Trello](https://trello.com/b/l0nWcfbK/project-6-machine-learning)  
