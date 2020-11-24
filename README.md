# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?<br>
The variable considered for the target in the model is the "Is_Successful".

- What variable(s) are considered to be the features for your model?<br>
The variables that are considered to be features for my model are: 
  - Application_Type
  - Affiliation
  - Classification
  - Use_Case
  - Status
  - Income_Amt
  - Special Considerations
  - Ask_Amt

- What variable(s) are neither targets nor features, and should be removed from the input data?<br>
Variables that are neither targets nor features and were removed from the input data are EIN and Name.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?<br>
Below is a chart showing the different neurons, layers, and functions used in the various models used to try and achieve the target model performance of 75%.  
<img src = "https://github.com/jennfrbrown/Neural_Network_Charity_Analysis/blob/main/ReadMe%20Images/Comparison.PNG">

- Were you able to achieve the target model performance?<br>
No, the target model performance of 75% was not achieved using the neurons, layers, and activation functions summarized above.

- What steps did you take to try and increase model performance?<br>
Several models were used to try to reach the 75% accuracy score. For the neural network model, several hidden layers were attempted. Neurons were adjusted. Number of epochs were increased. Different optimizers were tried. The activations attemped were 'relu' and 'tanh'. Also, an attempt was made to drop rows of noisy data from the ASK_AMT column. This was unsuccessful and the attempt was abandoned.

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
