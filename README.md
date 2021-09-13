# customer-loan-defaults
In this repository I have built several classification models to predict whether a customer will default on their loan.

This analysis is based on the  “All Lending Club loan data”. After the initial data pre-processing and feature
engineering phase, I have compared the performance of three different classification models, namely:
i) Logistic Regression;
ii) Decision Tree
iii) Random Forest

I have observed that the data in use is highly imbalanced (i.e. 85.2% of the total loans belong to the no-default category).
This implies that the minority class (i.e., defaulting loans), is significantly underrepresented, thus giving rise to imbalanced
classification. Creating a synthetic balanced dataset significantly increases the performance of the three baseline
classifiction models. 

Moreover, two other enhancements are performed: i) feature engineering and ii) hyper-parameter optimisation
using RandomisedSearch. These enhancement further increase the classification accuracy. 
I have finalised the report by performing an interpretability analysis on the best performing model. 
My analysis confirms that the best selected model (i.e. enhanced Random Forest Classifier) is interpreting the phenomenon in a sensible way in relation to
domain knowledge and human reasoning.
