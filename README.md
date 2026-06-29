# Credit-card-churn-prediction-model-using-Logistic-Regression-and-Decision-Tree
A Predictive Modelling poster narrating churn prediction model performance
The objective
To predict churn of credit card users and evaluate churn prediction model performance using Logistic regression and Decision tree.
Banks have a crucial need to practice customer relationship management (CRM) to reduce churning rate and improve customer retention. To formulate correct CRM policies, the bank is required to observe and predict the customers’ churning intention and traits (stop using or switching to another credit card company) accurately so that it can understand customers showing such traits for churning.
The churn prediction model is effective when it is powerful and constructed with high accuracy and lowest misclassification cost. The model can predict future behaviors and traits of customers, and bank can use this prediction model to retain customers and profits.

Data and models
Data source contributed from a China commercial bank with 60 million customers in data warehouse dated from January 2005 to April 2008 are reasonably reliable. However, data quality of personal data is poor due to incomplete fields and false data provided.
The predictive model mentioned in the study are designed from the Loss (or Cost) function which uses the churn rate, type I error, type II error and economic factors to calculate misclassification cost.
The formula of Loss function also referring to misclassification cost:
Loss (or Cost) = BesPave +M/(Ge_f+B(1-e_s))Gef
The logit transformation (odds ratio): g(x) = In (π(x))/(1-π(x)) logit P = InP_x/(1-P_x )
During the modelling process, Stepwise method was adopted to select from 95 variables, thereafter six types of models were constructed using different types of variables.

Results
Model 6 is chosen as the best model in both logistic regression and decision tree as it demonstrates strong predicting power and outweighs the other models for high accuracy, and low misclassification cost. Hence, Model 6 will allow a better understanding of churners’ profile and can be used to plan targeted marketing strategies for future customer retention and profitability.

Limitations
The study faced imbalanced data proportion, thus it is required to perform data sampling in 1:1 proportion and extracted balanced data samples to achieve higher testing accuracy. After data sampling, the data mart will contain total of 5456 samples to be used in the training set comprising of 215 samples from churners and 244 samples from non-churners, and the remaining 4997 samples comprising of 4772 usual customers and 225 churners to be used in a testing set.
The study also faced the problem of multicollinearity for its large VIF variables resulting in many variables required to be deleted.

Conclusion
Both the logistic regression and decision tree model can achieve optimal predictive results to solve the research problem.
Model 6 predicts well in both logistic regression and decision tree as observed by the prediction performance. Although there were only slight variations in results, for model 6 in a decision tree, the average error rate and the misclassification cost measured are observed to be higher than the logistic regression. Overall, we conclude that churn prediction model using logistic regression predicts better than decision tree model.

References
Nie, G., Rowe, W., Zhang, L., Tian, Y., & Shi, Y. (2011). Credit card churn forecasting by logistic regression and decision tree. Expert systems with applications, 38(12), 15273-15285
George Hess, Karthryn Tosney, Leon Liegel (2013), Creating effective poster presentations An effective abstract Retrieved from
 https://projects.ncsu.edu/project/posters/EffectiveAbstract.html
Chan, S.P., Tan, S.c., Wang, D., & Ren, J. (2021). ANL307 Predictive modelling (study guide). Singapore: Singapore University of Social Sciences Release V1.7 Build S1.0.5, T1.5.21
Yahoo search engine. (n.d.) Poster for predictive modelling Retrieved from
https://sg.images.search.yahoo.com/search/images;_ylt=AwrPh9fhMiFgAHwAWi4j4gt.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3BpdnM-?p=poster+for+predictive+modelling&fr2=piv-web&fr=yfp-t
#
