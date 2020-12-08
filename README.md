# Neural_Network_Charity_Analysis
## Overview of the Analysis
In this analysis we are creating a neural network in order to analyze a set of data of a company named Alphabet Soup. This company have donated some money to different companies and has created a data file that describes some characteristics of the companies to which they donated the money and if the outcome of the project to which they donated was successful or not. The purpose of this analysis is to create a model that will help Alphabet Soup decide which companies not to donate because most likely the outcome of the donation wil not be successful. 
## Results
##### Data Preprocessing:
  * For our model that target values are the ones in the IS_SUCCESSFUL column.
  * The features or our model are the ASK_AMT, APPLYCATION_TYPE, AFFILIATION, ORGANIZATION, INCOME_AMT columns.
  * The variables that are neither targets nor features are the EIN, NAME and as I considered in the deliverable 3 the STATUS. Therefore, they should be eliminated.
  
##### Compiling, Training, and Evaluating the Model:
  * For the neural network model I chose 2 layers and 100 nodes for the first layer and 80 nodes for the second layer because of the rule of thumb.
  <img width="943" alt="Screen Shot 2020-12-07 at 8 53 27 PM" src="https://user-images.githubusercontent.com/68616522/101428333-80304e80-38ce-11eb-8cdf-6d8dff5ffdbf.png">

  * In despite three diiferent attempts I was not able to reach the target model preformance.
  <img width="627" alt="Screen Shot 2020-12-07 at 8 53 55 PM" src="https://user-images.githubusercontent.com/68616522/101428337-81617b80-38ce-11eb-866d-de8920bc29c7.png">
  
  * In order to increase the model performance I deleted the STATUS column; also, I increased the nodes and used a third layer. Moreover, I increased the epochs and changed the activation of the layers.
  
## Summary
All in all in despite of our efforts to increase the model performance; the model accuracy remained under 75% which for the purpose of the company should be enough since it does not matter if the company rejects to fund some projects that would be successful. The money that is not used in those projects would be used in other projects that have more characteristics of being successful.
For a different model that could solve this classification problem we should check if there are more columns that should be eliminated. Also, more data should be obtained from the companies in order to obtain a better performance.
