# Predicting-Sale-Prices
Predicting sale prices of home with regression techniques

The dataset used in this project describes real estate in Ames, Iowa and includes 79 explanatory variables encompassing nearly every aspect of residential homes from style, year_built, number_of_rooms to roof_type. In predicting sale prices, I employed an ensemble learning strategy, leveraging a diverse set of models. 

Starting with Normal Linear Regression, I established a foundational understanding of linear relationships. For feature selection, LassoLars and Elastic Net introduced sparsity through LASSO regularization. Kernel Ridge Regression accommodated non-linear patterns. The ensemble approach integrated Gradient Boosting, Adaboost, XGBoost, LightGBM Regressor, and Random Forest, each renowned for capturing complex patterns. This ensemble, fine-tuned through hyperparameter adjustments, provided a resilient and accurate framework for predicting sale prices, capitalizing on the collective strengths of its constituent models.

To validate my predictive models, I implemented k-fold cross-validation, dividing the dataset into subsets to assess performance across diverse data partitions and mitigate overfitting. Various metrics were employed for evaluation, including Mean Squared Error (MSE) and R-squared for comprehensive insights into predictive accuracy. Mean Absolute Error (MAE) further gauged model robustness. These metrics collectively facilitated model fine-tuning and the selection of the most effective ensemble for predicting sale prices in my project.
