# Neural_Network_Charity_Analysis
## Overview
The purpose of this analysis was to build a neural network to see if we could predict whether or not an application would be successful based on the loan type and the ask amount.
## Results
. The target variable is whether or not an application is successful
. The features of the model are ask amount and application type
. Variables like name, Id, and affiliation were not relevant to the analysis and were removed from the input data
. I used two activation layers for each model and then varied the number of nodes for each model
. I was unable to achieve the ideal model performance
. I changed the number of hidden nodes, decreased the number of epochs and varied which activation function was used to try and improve model performance
## Summary
Making changes did not significantly improve model performance, as each time the model failed to achieve 60 percent accuracy. We could try building a random forest model instead to see if that model could improve results. At the very least a random forest would show results in a much shorter timeframe.
