This Classification model will able to classify people based on the set of the attributes given in German Credit Dataset dataset. 
The German Credit Dataset for this classification model is taken from UCI (Machine Learning Repository). In this dataset we have 1000 instances 
with 20 attributes, these attributes consist of both numerical and non-numerical values. 
For this classification model I used Multilayer Perceptron (Neural Network) model. 
In Feature Analysis step I have applied two methods which are: 
- Finding and removing outliers
- correlation analysis of dataset. 

After applying these two methods I normalized some features in the dataset and then I split the dataset in two subsets, training and testing sets. 
For passing the data as input in Neural Network the data first have to be converted in vector form so after making two subsets of data, 
I transformed both subsets into vector form. The Neural Network for this project has 3 hidden layers, 1 output and 1 input layer. 
To prevent overfitting, I’m using Dropout layers in the Neural Network. Cross Validation is also being used to prevent overfitting. 
The model gave 73.94% training accuracy and 75% testing accuracy. 
The final total score was 17, out of 20 test points the model misclassified 5 data points and 15 data points were classified accurately. 
In 5 misclassified points 3 bad people were classified as good and 2 good people was classified as bad.
