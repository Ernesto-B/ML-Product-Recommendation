# ML-Product-Recommendation
## Problem
Emazon Online Shopping is a startup company with an e-commerce application.
They are attempting to increase their revenue through increased sales of their products.
One way to do this is through implementing personalized product suggestions for users. In
this case, the question becomes “which product category is a user most likely to purchase
from next?” By showing products from a category that a user is likely to purchase from
(based on their age, gender, income, location, and other metrics), users of the application
are more likely to increase their purchases and Emazon can increase their revenue.

As such, this project will be focusing on developing a personalized suggestion
experience by employing various machine learning models to predict which product
category a user is most likely to purchase from next, based on a wide variety of user data.
Examples of product categories include: technology, fashion, food, travel, and sports.

By completing this machine learning model, given that it is accurate in its
predictions, Emazon will be able to suggest and market products to users that have a
higher chance of being purchased. The use of this model would not only increase revenue
for their business but also drive customer satisfaction and loyalty due to the improved
marketing, tailored promotional offers, and targeted product recommendations. 

## Plan of Attack
1. Data Processing: cleaning up and transforming the dataset. Possibly engineering
new features.
2. Model Training: train the three models.
3. Hyperparameter Tuning: use cross-validation to optimize each model’s
performance.
4. Evaluation: Compare each model's performance across metrics such as accuracy,
F1 score, precision and recall and conclude the best model to use for this project’s
purpose. 

Dataset
The dataset used to train, test, and validate the model can be downloaded and
found at: https://www.kaggle.com/datasets/kartikeybartwal/ecommerce-productrecommendation-collaborative or directly from my project repository at
https://github.com/Ernesto-B/ML-Product-Recommendation > `user_personalized_features.csv`

## Models Used
- Logistic Regression (linear).
- Random Forest (non-linear).
- Gradient Boosting (non-linear). 

## Frameworks
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborne