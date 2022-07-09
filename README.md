# Neural_Network_Charity_Analysis
With my knowledge of machine learning and neural networks, I used the features in the charity_data dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Analysis


## Results
### Data Preprocessing
- The variable that is considered the target for my model is the "IS_SUCCESSFUL" column which contains a 1 or 0 for yes and no.
- The variables considered to be features for my model are every other column beisdes "IS_SUCCESSFUL".
- The variables that are neither targets nore features were the "EIN" and "NAME" columns, which were dropped.

### Compiling, Training, and Evaluating the Model
See picture for the Deep Learning Neural Network model I created:
![image](https://user-images.githubusercontent.com/99369565/178123301-8f87bc0e-423e-4974-bfb5-dd72684bb385.png)

![image](https://user-images.githubusercontent.com/99369565/178123379-c77c5abf-56d1-4561-9ba5-97c815d539f9.png)


See picture for the optimization attempt:
![image](https://user-images.githubusercontent.com/99369565/178123340-93fc5512-b9b3-48c9-8a82-dfc270fa1b78.png)

![image](https://user-images.githubusercontent.com/99369565/178123371-45c31b5f-e25d-40ea-8166-c0c3b0bc6496.png)


## Summary
The Deep Learning Neural Network model and optimization models resulted in very similar results with Loss: 0.5526067018508911 & Accuracy: 0.726064145565033 and Loss: 0.5621252059936523, Accuracy: 0.7261807322502136 respectively.
