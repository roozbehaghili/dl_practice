# Income Classification with Neural Networks

This project is a simple example of using a neural network to classify income levels based on demographic data. I used the [Adult Income dataset from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/2/adult) and built a neural network model in PyTorch to predict whether an individual's income exceeds $50,000 per year.

## Dataset

The dataset used in this project is the **Adult Income dataset** from the UCI Machine Learning Repository. It includes information about individuals such as age, education, marital status, and occupation, which are used as features to predict income.

### Features

- Age
- Work class
- Education level
- Marital status
- Occupation
- Relationship status
- Race
- Sex
  
...

### Target

- Income (>50K or ≤50K)

## Model

I built a simple feedforward neural network using PyTorch, consisting of two hidden layers.
The model was trained for **10 epochs** and achieved an accuracy of **85%** on the test set.

## Future Improvements

- Experiment with deeper networks and additional layers.
- Tune hyperparameters such as learning rate, batch size, and the number of epochs.
- Add dropout for improved generalization.
