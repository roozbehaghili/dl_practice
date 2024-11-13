# Titanic Survival Prediction using Excel!

This folder contains an Excel file for predicting passenger survival on the Titanic, based on the [Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic). Using only Excel formulas, it shows three different approaches to classifying whether a passenger would survive or not:

## File Contents

The Excel file includes three tabs, each representing a unique method of calculating predictions:

### 1. **Linear**
   - This sheet uses a simple linear function to predict survival probabilities. It shows a straightforward approach without complex neural network structures.
   - **Method**: 
      - A single linear equation with weighted inputs.

### 2. **NNet (Neural Network)**
   - A basic neural network with three layers, each applying linear transformations followed by ReLU activation functions.
   - **Method**: 
      - Three linear transformations followed by three ReLU activation functions.
      - Calculations are done using the `SUMPRODUCT` function to handle the linear layers.

### 3. **MMult (Matrix Multiplication)**
   - **Method**:
      - Similar to the NNet sheet, this tab implements the same three-layer neural network with ReLU activations.
      - Utilizes `MMULT` (matrix multiplication) for calculations, resembles neural network operations used in Python.

## Getting Started

1. Download the Excel file.
2. Open it in Excel and explore each tab to see how predictions are calculated.
3. Modify the input values if you like to test different scenarios. After modifying the inputs, you can use `Solver` (found under Data -> Analysis Tools) to minimize the loss, similar to optimizing with a gradient, to find the best values.