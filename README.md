# Machine-Learning-Projects

  The following proposal dwells on the business background, the business
problem, and the strategy to solve the problem. The background of the business is 
the Citi Bike in New York, which people use for transportation. The business problem
revolves around running machine learning models to make predictions that favorably
affect the business.

  The domain knowledge of Citi Bike sharing is a classification dataset that
consists of an imbalanced label in the dataset. The analysis of the dataset assists
analysts in predicting something valuable about customers that can be used to make
decisions that strongly affect the business dynamics. In this case, the CITI bike-sharing
dataset was used to predict the user type of the customers, such as subscribers
or general.

  The reason behind choosing to work on the above-mentioned prediction problem
is to make better business decisions. Solving the problem enhances the accuracy of
figuring out the logistics to provide enough bikes to avoid the supply-over-demand
curve. Knowing what locations or factors help trigger each kind of user type
increases revenue.

  The potential plan for the approach is to load the dataset, pre-process the
dataset, split the dataset, and fit the dataset in machine learning models, using hyperparameter
tuning for higher accuracy. The data was downloaded from the Kaggle website in CSV
format and loaded into Jupyter Notebook. The data was pre-processed by checking for
null values, dropping duplicates, and performing exploratory data analysis for each
column. The dataset was split into train and test to avoid data leakages. The data was
fit into various machine learning models such as Logistic Regression, Decision Trees,
XGBoost, and Random Forests. Hyperparameters of the machine learning model that
showed the most accurate prediction, Random Forest, were chosen to apply cross-validation
to increase the effectiveness of the prediction.

  Therefore, the New York-based Citi Bike company’s dataset was analyzed. 
To predict the user type and what factors trigger the increase in user types. By
preprocessing the dataset and running machine learning models for effective prediction.
