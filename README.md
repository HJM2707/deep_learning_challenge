# deep_learning_challenge

## Deep Netwok Analysis Report:

#### The study was based on predicting through the neuronal network analysis on the charity funding data. 
#### The outcome of the analysis is the either success in recieving the funds by Alphabet Soup.
### What variable(s) are the features for your model?
#### 'IS SUCCESSFUL' column is the target variable to be predicted
### What variable(s) should be removed from the input data because they are neither targets nor features?
#### All the other columns except dropped 'IS SUCCESSFUL' (performed as our target), 'EIN and 'Name'(which has large number of uniqueness needed to be dropped otherwise can disturb the performance of neural network) has performed as features in the analysis for prediction
## Results:
### 1st compile training reference (Starter_code.ipynb)
![compile_training](https://github.com/HJM2707/deep_learning_challenge/assets/118155597/52d84e09-33a0-4830-8ad2-25c54682f699)

### Were you able to achieve the target model performance?
#### The First target model performance was recorded to score 72% with 0.553 loss of the data using the default training and test split size.

short/initi_model_accuracy_stats.png
![initi_model_accuracy_stats](https://github.com/HJM2707/deep_learning_challenge/assets/118155597/7bbb0996-6377-4903-8f86-c84077364eef)

### Second attempt of optimization 
![optimized_compile_training](https://github.com/HJM2707/deep_learning_challenge/assets/118155597/3a47c069-d985-43e0-91b5-82c5564e923d)
#### Which achieved 70% accuracy
![optimized_models_accuracy](https://github.com/HJM2707/deep_learning_challenge/assets/118155597/51660bb4-6c65-4a59-a41c-bb3fee8095d9)

### I added third optimized training using 'Names' embedded in the analysis and the accuracy results went over 80%

![final_accuracy_stats](https://github.com/HJM2707/deep_learning_challenge/assets/118155597/04c5fbe2-e804-4df7-89c3-ae30726aacea)

