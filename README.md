# SmartCartClusteringSystem
1. SmartCart is a growing e-commerce platform serving customers across multiple countries. The company collected extensive customer data consisting of 2240 customer records and 22 attributes including demographics, purchase behaviour, website activity and response.
2. Currently, SmartCart uses generic marketing and engagement strategies for all customers, without clearly understanding different customer behaviour patterns. This results in inefficient marketing, missed opportunities to retain high-value customers, and delayed identification of churn-prone users.
3.  To solve this , SmartCart aims to build an intelligent customer segmentation system under unsupervised learning. This system will analyse historical customer transaction data and group customers into meaningful clusters based on purchasing behaviour, engagement levels, and loyalty indicators.

# Dataset Description 
Each row in the dataset represents a customer and contains multiple attributes describing their spending and activity on platform.
# 1. Customer Demographics 
| Feature          |       Description            |
|------------------|------------------------------|
| ID               |   unique customer identifier |
|Year_Birth        | year of birth customer       |
| Education        |  Highest level achieved      |
| Marital_Status   |    Marital Satatus of customer|
| Income           | yearly household income      |
| Kidhome          | NO. of small children        |
| Teenhome         | no. of teenagers             |
|Dt_Customer       |  data when enrolled          |

# 2. Purchase Behaviour 
|Feature            | Description                  |
|-------------------|------------------------------|
| MntWines          | amount spent on wine products|
| MntFruits         | amount spent on fruits       |
| MntMeatProducts   | amount spent on meat products |
| MntFishProducts   | amount spent on fish products |
| MntSweetProducts  | amount spent on sweets       |
| MntGoldProducts   | amount spent on gold         |

# 3.  Purchase Frequency 
| Feature              | Description                 |
|----------------------|-----------------------------|
|NumDealsPurchase      | purcahses using dicounts    |
| NumWebPurchase       | purchases using through website |
| NumCatalogPurchase   | purchases using catalog     |
| NumStorePurchase     | purchase in stores          |
| NumWebVisitsMonth    | visits per month            |

# 4. Customer Feedback And Constants
| Feature                | Description                   |
|------------------------|-------------------------------|
| Recency                | No. of days since last purchase|
| Complain               | In last two years (yes=1,No=0)  |
