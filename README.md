# Marketing-Campaign-Analytics

## About The Dataset
- Marketing Campaign data from 2012 to 2014

### Content 
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response (target): 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain: 1 if customer complained in the last 2 years
- DtCustomer: date of customer’s enrolment with the company
- Education: customer’s level of education
- Marital: customer’s marital status
- Kidhome: number of small children in customer’s household
- Teenhome: number of teenagers in customer’s household
- Income: customer’s yearly household income
- MntFishProducts: amount spent on fish products in the last 2 years
- MntMeatProducts: amount spent on meat products in the last 2 years
- MntFruits: amount spent on fruits products in the last 2 years
- MntSweetProducts: amount spent on sweet products in the last 2 years
- MntWines: amount spent on wine products in the last 2 years
- MntGoldProds: amount spent on gold products in the last 2 years
- NumDealsPurchases: number of purchases made with discount
- NumCatalogPurchases: number of purchases made using catalogue
- NumStorePurchases: number of purchases made directly in stores
- NumWebPurchases: number of purchases made through company’s web site
- NumWebVisitsMonth: number of visits to company’s web site in the last month
- Recency: number of days since the last purchase

## Analysis Steps
1. Load The Data
2. Clean The Data 
    1. Check the duplicates
    2. Delete Columns with only one value
    3. Delete Columns That will not be used
    4. Handle Null Values
3. Prepare The Data For Analysis
    1. Calculate the age of customer in 2014 To cluster the customer based on their ages
    2. Create Year, Month and Quarter For Analysis
4. Analyze The Data
    1. Show basic info about the data
    2. Visualize the data 
    3. Describe Numerical and Categorical data
    4. Analyze the data based on the target
5. Feature Engineering For Predictive Machine Learning Model
    1. Classify The Customer Based on there ages (Young, Middle, Old)
    2. Drop Unnecessary Columns In The Model
    3. Create new features will be used in the model        
