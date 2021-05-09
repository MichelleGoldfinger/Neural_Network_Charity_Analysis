# Neural_Network_Charity_Analysis
# Deliverable 4: Written Report on Neural Network Model

## Overview of the analysis: Explain the purpose of this analysis.

Using the features in the dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Deliverable 1 is where I preprocessed the data for the neural network model. Deliverable 2 is where I compiled, trained, and evaluated the model. Deliverable 3 is where I optimized the model.

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing:
What variable(s) are considered the target(s) for your model?

The variable that was used as the target for this model was the IS_SUCCESSFUL data.

<img width="809" alt="Screen Shot 2021-05-09 at 3 26 49 PM" src="https://user-images.githubusercontent.com/75905911/117584435-03064100-b0db-11eb-9b7d-b170e1c7fd77.png">


What variable(s) are considered to be the features for your model?

The following variables were used as features in this model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, IMCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMOUNT.

What variable(s) are neither targets nor features, and should be removed from the input data?

I removed the EIN and NAME columns from the original dataset because they were neither targets nor features.

<img width="829" alt="Screen Shot 2021-05-09 at 3 27 57 PM" src="https://user-images.githubusercontent.com/75905911/117584450-26c98700-b0db-11eb-8995-129db92df805.png">


#### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

I used 5 neurons, 15 layers and relu activation functions for my layers and sigmoid activation function for the output layer. I chose these because of the rule that layers should be 2-3x the amount of neurons.

<img width="1387" alt="Screen Shot 2021-05-09 at 3 29 57 PM" src="https://user-images.githubusercontent.com/75905911/117584509-7314c700-b0db-11eb-9dd1-f5ebf8cd1fc1.png">

Were you able to achieve the target model performance?

With all the parameters that I choose the model had a 70% accuracy. The target performance was 75% so I did not achieve this performance.

<img width="819" alt="Screen Shot 2021-05-09 at 3 30 47 PM" src="https://user-images.githubusercontent.com/75905911/117584774-c8050d00-b0dc-11eb-88c4-113704ed93c8.png">



What steps did you take to try and increase model performance?
I did three different optimization trails. The first was to change the APPLICATION counts from 500 to 5000. I also changed the CLASSIFICATION counts from 1000 to 2000.

<img width="1398" alt="Screen Shot 2021-05-09 at 3 32 35 PM" src="https://user-images.githubusercontent.com/75905911/117584612-f209ff80-b0db-11eb-84b1-b7a8c34b3dbd.png">

<img width="1380" alt="Screen Shot 2021-05-09 at 3 32 52 PM" src="https://user-images.githubusercontent.com/75905911/117584609-eae2f180-b0db-11eb-9d1a-9c9da8aae910.png">


The second optimization was to 	increase the number of hidden layers from 15 to 100.

<img width="1379" alt="Screen Shot 2021-05-09 at 3 34 46 PM" src="https://user-images.githubusercontent.com/75905911/117584689-5dec6800-b0dc-11eb-842d-92dc55334305.png">


The third optimization I performed was to change the number of epochs from 	100 to 200.

<img width="800" alt="Screen Shot 2021-05-09 at 3 37 37 PM" src="https://user-images.githubusercontent.com/75905911/117584729-84120800-b0dc-11eb-849f-4d6382dd52a6.png">


## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

For my first-pass the model performed at 70% accuracy. After changing the APPLICATION counts from 500 to 5000 and CLASSIFICATION counts from 1000 to 2000. This change led to a 73% accuracy score. After changing the number of hidden layers from 15 to 100 the model’s accuracy score was 70% . After changing the number of epochs from 100 to 200 the accuracy score was. Therefore, the most beneficial optimization was. The least beneficial optimization was.
