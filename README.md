Neural Network Model Report:


Overview of the analysis: The purpose of this analysis is to predict which applicants have the highest chances of succeeding when they apply for funding with the nonprofit Alphabet Soup. A dataset is provided, this dataset will be trained and tested to provide classification of candidates with more chance of success versus candidates with lower chances. 

Results: Using bulleted lists and images to support your answers, address the following questions:
Data Preprocessing
What variable(s) are the target(s) for your model? The column names “IS_SUCCESSFUL” stores the applications considered successful or unsuccessful.
What variable(s) are the features for your model? The application type, the affiliated sector of industry, the government organization classification, the use case for funding, the organization type, the status, the income, the funding amount requested and if there are any special considerations to the application (binary, yes or no).
What variable(s) should be removed from the input data because they are neither targets nor features? The application number and name of applicant should be removed from the dataset for machine learning purposes
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why? We have used two layers, the first with 80 neurons and second with 30 neurons, aside from the output layer. The first layer used Relu for activation function and the second used Elu. Relu, which stands for Rectified Linear Unit is a method considered efficient, easy to implement and that can take into consideration the non linearity aspect of a dataset. The combination with a different method, Elu (Exponential Linear Unit) increases the chances of accuracy of the trained model.
Were you able to achieve the target model performance? The model accuracy achieved is 72%.
What steps did you take in your attempts to increase model performance? We tested the combination of different activation methods and also tested changing the epochs quantity to 50, 100 and 300
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
The results were considered less than ideal due to the model loss rate of roughly 56% and accuracy of 72%. We would recommend the utilization of Random Forest to further explore methods to increase the accuracy of our machine learning model.
