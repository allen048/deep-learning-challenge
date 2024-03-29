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

### Summary
The aim for this deep learning model was to acheive a target of 75%. In working with this model, it produced 73%. Even though, not being successful in achieving our target, I feel that if we continued working on this project it would optimistically be possible to reach the desired goal. Additionally, we could implement optimization algorithms, data augmentation, and hyperparameter tuning. By using these potential strategies, we could possibly improve our neural network model.

• Module 21 Challenge Citations:

Website Citation: https://bootcampspot.instructure.com/courses/4938/assignments/61924?module_item_id=1077599

'Title:<Alphabet_Soup_Charity.ipynb> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/deep-learning-challenge/blob/main/Alphabet_Soup_Charity.ipynb

'Title:<AlphabetSoupCharity_Optimization_01.ipynb> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization_01.ipynb

'Title:<AlphabetSoupCharity_Optimization_02.ipynb> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization_02.ipynb

'Title:<AlphabetSoupCharity_Optimization_03.ipynb> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization_03.ipynb

'Title:<README.md> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/deep-learning-challenge/blob/main/README.md

OpenAI. (2024). ChatGPT (Mar 2024 versions) [Large language model]. https://chat.openai.com/chat


