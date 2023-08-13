## SUPERSTORE MARKETING PROJECT by KOSSY AJULUCHUKWU
![](storeimage.jpeg)

## CONTEXT

A SuperStore located in the SubUrban area in the US is planning on improving their revenue for their year end sales. The Marketing Department introduced a promo campaign which provide a 30% discount on all purchases. Cost has been set aside for the marketing team to engage existing customer via Telephone calls to sell the promo discount offer. However this cost need to be managed, hence the Marketing Manager wants you to build a model that can predict customers that will respond positively to the discount offer so that further engagement can be made to those specific customers to close the sales. This will help reduce the time and cost of scouring and engaging all the customers in the company's database for sales lead.

## OBJECTIVE

In this notebook, We will be building a model to predict the likelihood of a customer responding positively and purchasing the Gold membership discount offer, also identifying the different factors which affect the customer's response. This prediction will enable the Superstore Marketing team to save cost and time on telephone engagement to the right set of customers.

####  Dataset description
Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise

ID - Unique ID of each customer

YearBirth - Age of the customer 

Complain - 1 if the customer complained in the last 2 years 

DtCustomer - date of customer's enrollment with the company

Education - customer's level of education

Marital - customer's marital status

Kidhome - number of small children in customer's household

Teenhome - number of teenagers in customer's household

Income - customer's yearly household income

MntFishProducts - the amount spent on fish products in the last 2 years

MntMeatProducts - the amount spent on meat products in the last 2 years

MntFruits - the amount spent on fruits products in the last 2 years

MntSweetProducts - amount spent on sweet products in the last 2 years

MntWines - the amount spent on wine products in the last 2 years

MntGoldProds - the amount spent on gold products in the last 2 years

NumDealsPurchases - number of purchases made with discount

NumCatalogPurchases - number of purchases made using catalog (buying goods to be shipped through the mail)

NumStorePurchases - number of purchases made directly in stores

NumWebPurchases - number of purchases made through the company's website


NumWebVisitsMonth - number of visits to company's website in the last month

Recency - number of days since the last purchase


## FRAMEWORK

We will be using PACE framework to work on this project. This is a framework by GOOGLE for data alalysis projects.

**P** - Plan Stage

**A** - Anayze Stage

**C** - Construct Stage

**E** - Execute Stage

## 1.  PLAN STAGE

1. what is the goal of the project?
2. what is the source of dataset?
3. are there ethical considerations?

* Remove duplicates
* Address missing data
* Remove outliers


1.  We will be building a model to predict the likelihood of a customer to giving a positive response to purchase the Gold membership discount offer and also to identify the different factors which affect the customer's response. This prediction will enable the Superstore Marketing campaign to save cost and time on telephone engagement to the right set of customers.

2. The data set is a Superstore Marketing campaign dataset dowloaded from Kaggle. This data set can be gotten from this link https://www.kaggle.com/datasets/ahsan81/superstore-marketing-campaign-dataset?select=superstore_data.csv

3. No ethical challenges as all dataset are evenly represented across range of variables. e.g Marital status, sex etc.

TABLEAU
The tableau visualization can be access via this link
![image](https://github.com/kkkossy/SUPER-STORE-MARKETING-CAMPAIGN/assets/118011823/32048aae-14d5-4e28-9ae2-043ccfedb87d)


