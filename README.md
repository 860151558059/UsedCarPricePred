# UsedCarPricePred
This project uses Python and Machine Learning to predict the price of a used car based on its details like model year, fuel type, kilometers driven, transmission, and more.
In this project the two models are compared -
First one is Linear Regression Model and The Second One is Random Forest Regressor 
so We choose the best mode the model which is more accuret.

The main objective of this project is to predict the selling price of a used car using Machine Learning. By taking important car details like the year of purchase, fuel type, kilometers driven, transmission type, and number of owners, the model gives an estimated price.

This helps people, especially in India, to make smarter decisions while buying or selling second-hand cars, ensuring they get a fair deal based on data, not just guesswork
## Features Used for Prediction:
- Year of Purchase  
- Present Price  
- KMs Driven  
- Fuel Type (Petrol/Diesel/CNG)  
- Seller Type (Dealer/Individual)  
- Transmission (Manual/Automatic)  
- Number of Owners

## 🤖 ML Model Used:
- **Random Forest Regressor**
- Gives good accuracy with real-world data
- Works well with limited features

## Linear regression :
is a type of  supervised machine-learning algorithm that learns from the labelled datasets and maps the data points with most optimized linear functions which can be used for prediction on new datasets. It assumes that there is a linear relationship between the input and output, meaning the output changes at a constant rate as the input changes. This relationship is represented by a straight line.

## Random Forest Regressor : 
Random Forest is a machine learning algorithm that uses many decision trees to make better predictions. Each tree looks at different random parts of the data and their results are combined by voting for classification or averaging for regression. This helps in improving accuracy and reducing errors.

Create Many Decision Trees: The algorithm makes many decision trees each using a random part of the data. So every tree is a bit different.
Pick Random Features: When building each tree it doesn’t look at all the features (columns) at once. It picks a few at random to decide how to split the data. This helps the trees stay different from each other.
Each Tree Makes a Prediction: Every tree gives its own answer or prediction based on what it learned from its part of the data.
Combine the Predictions:
For classification we choose a category as the final answer is the one that most trees agree on i.e majority voting.
For regression we predict a number as the final answer is the average of all the trees predictions.
Why It Works Well: Using random data and features for each tree helps avoid overfitting and makes the overall prediction more accurate and trustworthy
