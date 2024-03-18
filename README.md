# Real Estate Analysis in King County, USA

In this analysis, we were provided with a dataset containing information on more than 21,613 house sales in King County, USA. Our primary objectives were as follows:

a) Evaluate the performance of two regression models, namely linear regression and neural networks, for predicting house prices. Determine which model provides better estimation performance and provide reasoning for the choice.

b) Transform the house price attribute from a numeric value into a nominal attribute, categorizing houses with prices of 450,000 or more as "High_Price" and those with prices less than 450,000 as "Low_Price." Evaluate the performance of two classification models, neural networks, and another model of choice, for predicting these price categories. Identify which model exhibits superior classification performance and explain the rationale behind the selection.

**Proposed Approaches:**
For both problems, we applied neural network models and explored various experiments to compare their performance with other machine learning algorithms, including linear regression, random forest, and logistic regression.

**Major Findings:**
In addressing the first problem of predicting house prices, we found that a neural network model with multiple layers, each comprising many neurons (where one neuron corresponds to a linear regression algorithm), outperformed other models. By adding more layers to the neural network, the model was better learn from historical data and patterns, resulting in higher accuracy and lower Mean Absolute Error (MAE). Therefore, this "Best Model" achieved the highest correlation between predicted and actual values, as well as the lowest MAE, making it the preferred choice for price estimation.

For the second problem of classifying houses as "High_Price" or "Low_Price" based on the transformed price attribute, we compared the performance of two classification models: neural networks and other models (logistics regression and random forest). Model 3, the neural network, demonstrated superior performance with higher accuracy, a higher Kappa score indicating better agreement with true values, and a slightly higher F-Measure. Model 1, which used logistic regression, consistently lagged behind the other models in all three metrics.

In conclusion, based on the findings and evaluations, the adoption of neural network models, especially for price estimation and price categorisation, these models exhibit strong potential for enhancing decision-making processes in the real estate domain.
