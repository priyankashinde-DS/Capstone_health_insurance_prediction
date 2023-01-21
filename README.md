# HEALTH INSURANCE CROSS SELL PREDICTION


**Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimize its business model and revenue. Building a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle Insurance provided by the company**

## **Problem Statement**
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model **to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.**

### **What is Cross-Sell Prediction?**


 It is important to understand the problem domain and key terms used in the definition of a problem before beginning a project. In the financial services industry, cross-selling is a popular term.


## **Attribute Information**

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

## **Conclusion**

**Starting from loading our dataset, we firstly performed data cleaning and refactoring by outlier detection and normalization of data. Then we covered EDA, feature selection and algorithm selection, and hyperparameter tuning. The Accuracy score obtained for all models was in the range of 68% to 75% before tuning After tuning the models we were able to get an accuracy of approx 80%. But we selected our best model as the model with an accuracy score of 75% considering precision and recall as we have an unequal number of observations in each class in our dataset, so accuracy alone can be misleading.**

