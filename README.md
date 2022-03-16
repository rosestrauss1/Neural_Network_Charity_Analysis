# Neural Network Charity Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis was to use the features in a  dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL is the target for my model.

* What variable(s) are considered to be the features for your model?

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and ASK_AMT are features for my model.

* What variable(s) are neither targets nor features, and should be removed from the input data?

For my model, EIN, NAME, STATUS, and SPECIAL_CONSIDERATION columns are neither targets nor features and should be removed from the input data.

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?

For my model, I used four hidden layers and a few different activation functions: RELU, SELU, and SIGMOID. I chose to put in four hidden layers because

<img width="857" alt="Screen Shot 2022-03-16 at 1 33 39 PM" src="https://user-images.githubusercontent.com/92963227/158685873-957f8d5e-3fe6-44e0-9d0f-42843d4612ee.png">

* Were you able to achieve the target model performance?

I was not able to achive the target model performance of 75%. The highest accuracy my model achieved was 72%.

* What steps did you take to try and increase model performance?

To increase my model's performance, I tried adding more hidden layers and changing my activation function. I also tried changing the number of epochs, and adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model. I dropped the following columns:'SPECIAL_CONSIDERATIONS' and 'STATUS'.

## Summary: 

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

