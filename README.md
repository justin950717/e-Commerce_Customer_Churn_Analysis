# e-Commerce_Customer_Churn_Analysis
## Masters in DSBA Machine Learning Assignment

This is a Machine Learning case study to evaluate and compare the performances three supervised classification models based on Logistic Regression, Support Vector Machine and Decision Tree algorithms, in order to choose the most optimal model for predicting customer churn in the e-commerce domain. This study will be carried out using R-programming on R-studio, with its data sourced from Kaggle (https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction).

E-commerce is one of the booming industries in recent years due to the convenience and benefits it brings to consumers. The latest pandemic of 2019 - 2020 has even escalated the e-commerce industry into an essential service. That being said, the key factor to a successful and sustainable e-commerce business is to retain their existing customers as churning customers can be very detrimental to profit margins. One of the ways big players in the e-commerce domain prevent customers from churning is by examining customer’s buying patterns and then modelling those patterns to predict their probability of churning via Machine Learning. Thus, this enables companies to formulate marketing strategies to approach those customers that were predicted to churn, in the hopes of retaining them. However, there are many factors that can affect a customer's buying pattern, which this study aims to identify the various variables that may influence a customer's purchasing behavior in order to produce the best possible model for predicting customer churn in the e-commerce domain.

Hence, from the result of the evaluations, the pruned Decision Tree will be the model of choice in predicting e-commerce customer churn, as it managed to interpret most of the important factors that influences customer retention/churn (cited by literature). Moreover, the most influential factor in predicting customer churn is the tenure of the customer utilizing the e-commerce service.


No
Model
Accuracy (%)
1
Logistic Regression (LoR)
1.1
Default Model
87.13
0.848
2
Support Vector Machine (SVM)
2.1
Default Radial Kernel
89.59
-
2.2
Best Radial Kernel (Tuned)
92.75
0.862
3
Decision Tree (DT)
3.1
Default Tree
78.98
-
3.2
Pruned Tree
84.43
0.825
