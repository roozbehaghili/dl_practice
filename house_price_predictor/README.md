# Housing Price Prediction with Neural Networks

This project shows the use of a neural network to predict housing prices based on various features of the properties. The dataset used for this project contains information about housing characteristics such as the number of rooms, building age, and other property attributes. The model is built using PyTorch, and the goal is to predict the price of a house.

## Dataset

The dataset used in this project is the [California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices), which contains information about houses, including various attributes such as size and location.

### Features

- Number of rooms
- Number of bedrooms
- Square footage
- Building age
- Population
  
  ...

### Target

- **Price** (continuous numerical value representing the house price)

## Model

A simple feedforward neural network is built using PyTorch to predict housing prices based on the input features. The model consists of two hidden layers with ReLU activation functions and uses **Mean Squared Error (MSE)** loss for training.

I also implemented optimizer scheduler and early stop. The model is trained for **50 epochs** or until it is stopped using scheduler, with an Adam optimizer and achieved an RMSE (Root Mean Squared Error) value of **0.67** on the validation set.

## Future Improvements

- Experiment with deeper networks, more layers, and different activation functions.
- Implement feature engineering for better performance (e.g., interaction terms, polynomial features).
- Add regularization techniques like dropout to reduce overfitting.
