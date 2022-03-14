# Neural_Network_Charity_Analysis
## Overview of the analysis: 
The Alphabet Soup’s business team have more than 34,000 organizations that have received funding from Alphabet Soup over the years. We want to predict what kind of application can successfully get funded from Alphabet Soup. Thus, we will utilize deep learning in Neural Network Model to predict our result.
## Results: 
#### Data Preprocessing
- We use  IS_SUCCESSFUL as the target(s) for our model.
- All of column are as the features for our model,except IS_SUCCESSFUL.
- The columns ,EIN and NAME, are dropped in the beginning because those information won’t impact our predict process for IS_SUCCESSFUL. 
#### Compiling, Training, and Evaluating the Model
- I use two neurons. First one neurons has 80 hidden layers and apply relu activation function. Second one has 50 hidden layers and apply relu activation function. Additionally, it has one output layer and use sigmoid.
- This performance of target is 75%. I only get 54% so it doesn’t reach the target. 
Adding more neurons and layers and epochs received a lower accuracy,53%. 
## Summary: 
After using the deep learning in Neural Network Model, the accuracy is only 54%. That means this model of prediction is not correct. It has half chance to get a wrong answer. So I try to optimize the data to add more hidden layer or epochs, and change the activation function. The accuracy isn’t improvable. This model can be added many layers, but it is probably overfitting. Using more epochs can get higher accuracy, but sometime it needs a huge epoch, like over 1000 epochs. It will require to run the result several times. I will use another classifier model to predict this topic. It may save time and get higher accuracy.

