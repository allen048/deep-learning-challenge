# deep-learning-challenge

## Overview of the Analysis:

This assignment involved the knowledge of machine learning and neural networks, using the features in the provided dataset to develop a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The business team provided a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. In the dataset there are a number of columns that capture metadata about each organization, such as, EIN and NAME—Identification columns, CLASSIFICATION—Government organization classification, and IS_SUCCESSFUL—Was the money used effectively.

## Results:

### Data Preprocessing
•	What variable(s) are the target(s) for your model? IS_SUCCESSFUL

•	What variable(s) are the features for your model? All columns except IS_SUCCESSFUL, EIN, and NAME

•	What variable(s) should be removed from the input data because they are neither targets nor features? EIN and NAME

### Compiling, Training, and Evaluating the Model
•	How many neurons, layers, and activation functions did you select for your neural network model, and why? On my third optimization, I included 80 neurons and relu activation, two hidden layers with dropout of 0.3, and a output layer with a sigmoid activation function for binary classification. I followed this approach from Qasim, because I'm somewhat still unclear on the handling of this analysis.

•	Were you able to achieve the target model performance? I achieve 73% which is little lower than the 75% target model performance.

•	What steps did you take in your attempts to increase model performance? I updated the neurons to a higher optimal number of 150 in one instance and 100 in the final analysis to see if I could reach the target model performance. However, I was unsuccessful in this attempt. Also, I continued to update the layers as well which also did not aid in producing the desired result.




