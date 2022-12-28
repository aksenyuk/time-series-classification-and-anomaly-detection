# Classification and Anomaly Pattern Detection of Time Series

Co-authored-by: [@giminosk](https://github.com/Giminosk)

## Preamble

As a well-known data scientist, you were asked for help by a company producing candies. Some of their products are plagued with different types of defects.

The whole manufacture is equipped with sensors so there are several time series describing the process of producing candies.

They would like to achieve two goals:

- Have a predictive model which will tell them if a given candy has a defect and which ones

- Perform a root cause analysis - they would like to know what patterns in the data are related to defects

## Remarks

- A recurrent neural network (RNN) is used

- Patterns are of different length

- There is one defect related to a pattern occurring at two sensors simultaneously

- One candy can have zero, one or more defects at once

- The approach also works for other data after retraining

- For each class there is one pattern occurring in the data

## Requirements

- Classification of provided time series

- Explanation of prediction

- Neural network with at least one recurrent layer must be used in each step

- Not the whole logic is inside the neural network
