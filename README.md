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
      Since there are only positive cash inputs, only the Rectified Linear Unit (ReLU) and sigmoid functions can be used. 

  2.) Target model performance:
  3.) Steps to take to try and increase model performance

  ### Summary
  Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
