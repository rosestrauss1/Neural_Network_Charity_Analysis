# Neural Network Charity Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis was to use the features in a  dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?
* What variable(s) are considered to be the features for your model?
* What variable(s) are neither targets nor features, and should be removed from the input data?

For my model, EIN, NAME, STATUS, and SPECIAL_CONSIDERATION columns are neither targets nor features and should be removed from the input data.

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?

* Were you able to achieve the target model performance?

I was not able to achive the target model performance of 75%. The highest accuracy my model achieved was 72%.

* What steps did you take to try and increase model performance?

To increase my model's performance, I tried adding more hidden layers and changing my activation function. I also tried changing the number of epochs, and adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model. I dropped the following columns:'SPECIAL_CONSIDERATIONS' and 'STATUS'.

## Summary: 

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

