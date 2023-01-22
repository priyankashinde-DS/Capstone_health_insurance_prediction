# **HEALTH INSURANCE CROSS SELL PREDICTION**

![image](https://user-images.githubusercontent.com/87980985/213925810-954a577c-31a0-49df-9841-667cffb33a4c.png)


**In this project we build a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle Insurance provided by the company**

## **📖Introduction**
An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. There are multiple factors that play a major role in capturing customers for any insurance policy. Here we have information about demographics such as age, gender, region code, and vehicle damage, vehicle age, annual premium, policy sourcing channel. Based on the previous trend, this data analysis and prediction with machine learning models can help us understand what are the reasons for news popularity on social media and obtain the best classification model.

## **📖Problem Statement**

Our client is an Insurance company that has provided Health Insurance to its customers. Now they need the help in building a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimize its business model and revenue.


## **📖Data Description**

We have a dataset which contains information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc. related to a person who is interested in vehicle insurance. We have 381109 data points available.

1. id :	Unique ID for the customer

2. Gender	: Gender of the customer

3. Age :	Age of the customer

4. Driving_License	0 : Customer does not have DL, 1 : Customer already has DL

5. Region_Code :	Unique code for the region of the customer

6. Previously_Insured	: 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

7. Vehicle_Age :	Age of the Vehicle

8. Vehicle_Damage	 :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

9. Annual_Premium	: The amount customer needs to pay as premium in the year

10. PolicySalesChannel :	Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

11. Vintage :	Number of Days, Customer has been associated with the company

12. Response :	1 : Customer is interested, 0 : Customer is not interested

# **Steps Involved**

**1. Exploratory Data Analysis:**

**a. Understanding the data-**
In this step after loading the data I performed head, tail, columns, info, dtypes, describe functions to get basic information about our dataset.

**b. Checking for missing & duplicated values-**
Then I checked for missing values in our dataset using is null function. Some of our features had missing values that I filled with ‘unknown’

**2. Data Visualization**

In Data Visualization, firstly we explored the 4 numerical features: Age, Policy_Sales_Channel, Region_Code, Vintage. Further, we categorized age as youngAge, middleAge, and oldAge and also categorized policy_sales_channel and region_code. From here we observed that customers belonging to the youngAge group are less interested in taking vehicle insurance. Similarly, Region_C, Channel_A have the highest number of customers who are not interested in insurance. From the vehicle_Damage feature, we were able to conclude that customers with vehicle damage are more likely to take vehicle insurance. Similarly, the Annual Premium for customers with vehicle damage history is higher.

**3. Encoding categorical values**

We used one-hot encoding for converting the categorical columns such as 'Gender', 'Previously_Insured','Vehicle_Age','Vehicle_Damage', 'Age_Group', 'Policy_Sales_Channel_Categorical', 'Region_Code_Categorical' into numerical values so that our model can understand and extract valuable information from these columns.

**4. Model Building**

## **Conclusion**

**Starting from loading our dataset, we firstly performed data cleaning and refactoring by outlier detection and normalization of data. Then we covered EDA, feature selection and algorithm selection, and hyperparameter tuning. The Accuracy score obtained for all models was in the range of 73% to 79% before tuning After tuning the models we were able to get an accuracy of 80%. But we selected our best model as the model with an accuracy score of 79% considering precision and recall as we have an unequal number of observations in each class in our dataset, so accuracy alone can be misleading.**

## **References**

https://towardsdatascience.com

https://www.analyticsvidhya.com

https://machinelearningmastery.com
