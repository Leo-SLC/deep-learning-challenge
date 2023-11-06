# deep-learning-challenge
Module 21 Challenge: Deep Learning 


Overview of the analysis: The pursuit of this analysis was to determine what options would be wise investments for Alphabet soup based on a machine learning model. We used the dataset to build a model to predict which options are likely to succeed. 


Data Preprocessing

-What variable(s) are the target(s) for your model? 
	-We are looking to entities that are identified as "successful" in our Dataframe, meaning they were successful investments and worth using in our models. 

-What variable(s) are the features for your model?
	-IS_SUCCSESSFUL

-What variable(s) should be removed from the input data because they are neither targets nor features? 
	-The EIN and Name columns should be removed to allow the model to operate more efficiently and accurately. 


Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why? 
	- In the case of this analysis, a total of two hidden laters were used, with 80 Neurons and 30 Neurons used respectively. 

- Were you able to achieve the target model performance? 
	-This model was able to achieve a performance exceeding 78% (returning at roughly 79% to 80%), exceeding the required 75%. 
- What steps did you take in your attempts to increase model performance?
	-In this model the performance was sharply increased by adjusting the 'NAME' field as we did for application count and application classification. This allowed the model to fun much more efficiently. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation