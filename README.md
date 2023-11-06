# deep-learning-challenge
Module 21 Challenge: Deep Learning 


Overview of the analysis: The pursuit of this analysis was to determine what options would be wise investments for Alphabet soup based on a machine learning model. We used the dataset to build a model to predict which options are likely to succeed and therefore the model can be used to predict future options that will be effective. 


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

Summary: This machine learning model seems to have returned a model that can predict good options more than 75% of the time which exceeds the requirements, however, given that this is seeking investment information it might be worth pursuing an additional model/process for options that pass this level. This could be addressed by potentially adding neurons and hidden layers, or perhaps examining what changes occur when data in 'ORGANIZATION' or 'AFFILIATION' are binned. It is possible that company sponsored entities might have different changes of success than independents. The same for Organization type could be examined. 