# Classification_Models_on_Stock_Data

This code performs machine learning and evaluation on financial data for a list of stock tickers. The code first defines a function called machinelearn_df that extracts financial data for a specified stock ticker, adds technical indicators as features, splits the data into training and validation sets, and evaluates several classifiers using cross-validation. The function evaluates the classifiers using the following metrics: accuracy, precision, recall, F1-score, and balanced accuracy.

The code then iterates over a list of stock tickers and calls the machinelearn_df function for each ticker. For each ticker, the function performs machine learning and evaluation and prints the evaluation metrics for each classifier on the console.

The classifiers used in the code include logistic regression, linear discriminant analysis, k-nearest neighbors, support vector machines, random forest, gradient boosting, adaptive boosting, XGBoost, and multi-layer perceptron. The technical indicators used as features include moving averages, relative strength index, stochastic oscillator, and more.

Overall, this code provides a template for performing machine learning and evaluation on financial data for a list of stock tickers.
