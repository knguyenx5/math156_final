# math156_final
Experiments with Time-Series Forecasting for Math 156 final project

# Overview
In our covid19_forecast notebook, we attempt to forecast the number of daily new cases of COVID-19 within the United States. We wanted to experiment with two different forecasting algorithms, namely LinkedIn's Silverkite and Facebook's Prophet, to see which algorithm would perform best in this specific case study. To compare the algorithms' performances, we use the Mean Absolute Percentage Error metric, where this error will be calculated on a test set that is previously unobserved by the model. Throughout training, grid search is used to find the best parameters for each of our models and 10-fold cross validation is carried out as well.

# Note
There are multiple plotly graphs within our Jupyter Notebook, but they do not show up in Github when you open the notebook because Github performs a static render of the notebooks. However, these plotly visualizations are included in our final report.
