# deep-learning-challenge  Neural Network Model Report: Alphabet Soup
Challenge-21

The main objective of this analysis is to explor a neural network model that forcasts the likelihood of a client's progress based on their historical data. This analysis will help the NGO(Non-profit organisation named AlphabetSoup) a data-driven decision when evaluating future applications. By using the techniques of deep-learning, the user can classify the success and faiuler of the applicants based on the inputs/data. 

Overview of Data

With the use of Pandas and scikit-learn, the user found that the dataset contains some historical data of previous applications that has valuable informations like funding requirments, proejct goals and descriptions, application results like successful or unsuccessful and the target variable information. 

The analysis:

The analysis is devided by some steps:

1. Data Processing:
   In the analysis process the first and very importat step is to process the raw data so that it helps to give fruitful result. This step include various methodolofy such as data cleaning and handling missing values and removing irrelevate data. Here only the important and relevat features are selected for the improve model performance. The non-numerica data are encoding for into the categorical variables or numeric form and at the last scale the numerical features to ensure the uniformmity of the data. 

2. Development of the Model"
   The second step is to build a model which contains multiple layers such as Input layer. The Input layer accepts the preprocessed features. The Hidden layer helps to comprising dense layers with activation functions such as ReLu. And the Output layer is a single neuron with a sigmoid activation function to forcast the bunary outcomes.

3. Training and Testing:

 In this step the updated and clean data set can be use for training and testing for the final output or results. With a specific number of epochs and batch size the data set is evaluated and then the accuracy and loss were measured using the test data. The precision, recall and F1-score were also determined for the testing and evalution for the final result. 

Final Result:

The input layer: 43 features (Input_din = 43).
1st Hidden layer: 125 neurons, Relu activation, followed by batch normalization.
2nd Hideen layer: 125 neurons, Relu activation, with batch normalization. 
Out Layer: 1 neuron with sigmoid activation for binary classification. 
Adjusted network size, added dropout layers,modified learning rate, and increased epochs to improve accuracy. 

Initially, the model can achieve around 72% accurace. However, the goal was to achive 75% with subsequent optimizations incrementally imporving accuracy but falling just short of the goal. 

Summary:

The method like dropout regularization, adjusted learning rates, and early stopping-helped the model improve incrementally. To further enhance accuracy, additional preprocessing or experimentration with epochs may be useful in future. 

Reference:
BCS(Xpert Learning ASSISTANCE) and class activities, 
AI tools like Gamini and ChatGpt,
Classmates and peer assistance. 
