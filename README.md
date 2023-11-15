# deep-learning-challenge

Overview
In this challenge we are given a dataset of charity information. 
![image](https://github.com/IslandicMoon/deep-learning-challenge/assets/129472048/69c71a2a-aeee-4c64-ac34-313da2640316)

In order to begin creating a model that will provide an accurate understanding of which charities will be successful it is necessary to remove columns that have no significance to the model learning such as the name of the charity and its EIN. 

Once that is complete we must create two test variables that the model will learn from. These variables will be made up from which charities were successful and the amount asked columns. 


Results
The inital test was run and provided an accuracy of up to 49%. Once a second layer was added the ending accuracy was 53%. This 53% remained steady as a third layer was added. 
![image](https://github.com/IslandicMoon/deep-learning-challenge/assets/129472048/1096761c-945a-480c-90ad-553d0a3f4d13)

Summary
The model created is not an accurate predictor as to whether a charity would be successful based on its ask amount. It may be more appropriate to create a model on a different factor such as affiliation. This may have a more significant role on a charities success as there a number of ways an independent affiliated charity differs from a company sponsered charity. 
