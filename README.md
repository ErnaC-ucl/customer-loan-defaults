# customer-loan-defaults
Build classification models to predict whether a customer will default on their loan.

In this report we analyse the “All Lending Club loan data”, in order to build a model to predict
whether a customer will default on their loan. After the initial data pre-processing and feature
engineering phase, we compare the performance of three different classification models, namely:
i) Logistic Regression;
ii) Decision Tree
iii) Random Forest

We observe that the data in use is highly imbalanced (i.e. 85.2% of the total loans belong to the no-default category).
This implies that the minority class (i.e., defaulting loans), is significantly underrepresented, thus giving rise to imbalanced
classification. We observe that creating a synthetic balanced dataset significantly increases the performance of baselined
classifiction models. 

Moreover, two other enhancements are performed: i) feature engineering and ii) hyper-parameter optimisation
using RandomisedSearch. These enhancement further increase the classification accuracy. 
We finalise the report by performing an interpretability analysis on the best performing model. 
Our analysis confirms that the model is interpreting the phenomenon in a sensible way in relation to
domain knowledge and human reasoning.
