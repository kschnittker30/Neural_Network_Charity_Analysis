# Project Overview
Alphabet Soup is a non-for-profit foundation that raises and distributes funds to support various organizations.  In order to more accurtely predict sound investments in organizations, Alphabet Soup is looking to develop a neural network model. Neural networks are a set of algorithms modeled after the human brain to recognize patterns and features in input data.  Neural networks contain layers of neurons that perform individual computations to connect and weigh against each other until the neurons reach the final layer. Utilizing Alphabet Soup's CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years, a machine learning model will be developed to predict applicants that will be successful if funded by Alphabet Soup. The following deliverable will be created:

1: Preprocessing Data for a Neural Network Model

2: Compile, Train, and Evaluate the Model

3: Optimize the Model

4: A Written Report on the Neural Network Model

  # Results: Using bulleted lists and images to support your answers, address the following questions.

  ### Data Preprocessing
  * The target variable is 'IS_SUCCESSFUL'. 
  * The feature variables include 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'          
  * Features to remove from the input data include 'EIN', 'NAME'. These values are neither targets nor features.

  ### Compiling, Training, and Evaluating the Model
  1.) Neurons, layers, and activation functions selected:
      Since there are only positive cash inputs, only the Rectified Linear Unit (ReLU) and sigmoid functions can be used. Two layers were selected with neuron values of 80 and 30. Adjusting the layers and neuron values reduced accuracy.
      ![image](https://user-images.githubusercontent.com/99636479/176988757-c6c58945-dcf1-4b67-9d8a-571f3a8593f4.png)


  2.) Target model performance:
      The target model performance was not achieved, the accuracy was too low to achieve consistent results and the loss was high.
      ![image](https://user-images.githubusercontent.com/99636479/176988767-82d04039-077a-4242-b9ad-0cc01a505be9.png)

      
  3.) Steps to take to try and increase model performance
      A third layer was added to model, however the loss increased and the accuracy decreased. The activation was changed to all sigmoid, and again the loss increased and accuracy decreased. Changing the neuron values also increased the loss and decreased the accuracy. 

  ### Summary
  Adjusting the layers, activiations, neuron values did not improve the accuract of the model above 70%. This is a very low indicator to achieve reliable results for AlphabetSoup to base their decision making on.  It is recommended to utilize another model to predict successful candidates for funding.
