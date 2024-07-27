#Data Processing
1. What variable(s) are the target(s) for your model?
 - Target variable is the 'IS_SUCCESSFUL' column from application_df
2. What variable(s) are the features for your model?
 - Feature variables are every other column from application_df
 - This was defined by dropping the 'IS_SUCCESSFULL' column from the original dataframe
3. What variable(s) should be removed from the input data because they are neither targets nor features?
 - 'EIN' & 'NAME' columns were droppedd, because they were neither targets nor features in the dataset

#Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
 - First attempt had 8 hidden_nodes_layers and 5 hidden_nodes_layers2
 - These were randomly selected from whcih to iterate upon the second try
2. Were you able to achieve the target model performance?
- I was unable to acheive the 75% model accuracy target
3. What steps did you take in your attempts to increase model performance?
 - Adding more layers and removing more columns. Also added additional hidden nodes, along wtih switching the activation functions with each layer in hopes to achieve higher model accuracy.

 In Summary, the results of this model was roughly 73% in prediciting the classification model. Using a greater correlation output would naturally yeild better prediction accuracy. A way to attain this result would be by undertaking more data cleaning up front. Another way would be to use a model with different activation functions and iterating until the higher level accuracy is attained.
