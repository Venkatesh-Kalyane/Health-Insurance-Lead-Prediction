[Health Insurance Lead Prediction.pdf](https://github.com/Venkatesh-Kalyane/Health-Insurance-Lead-Prediction/files/6056818/Health.Insurance.Lead.Prediction.pdf)



1.Challenge/Problem Statement:

FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company. The company recommend health insurance to it's customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.

Once these leads are acquired, the sales advisors approach them to convert and thus the company can sell proposed health insurance to these leads in a more efficient manner.
Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:

Demographics (city, age, region etc.)
Information regarding holding policies of the customer
Recommended Policy Information


2. Information regarding the given Dataset:

1. Given Problem statement is a classification problem and the Target Variable is Categorical Variable
2. Presence of both Continuous and Categorical Variables
3. Presence of Null Values
4. Presence of Highly correlated Variables
5. Presence of Outliers
6. Dataset is imbalanced


3.Approcah to Solve the given problem statement:

I used 'Random Forest Classifier' to solve this problem statement because of following reasons:

1. It can handle both Continuous and Categorical Variables and Less likely to overfit
2. Robust to Outliers
3. Feature Scaling is not required
4. Require Less Parameter tuning
5. Imbalance issue can be handled using class_weight parameter


4.Target Customers/Industries:

The benefitted audience includes Finance industries.
