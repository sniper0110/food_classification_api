# food_classification_api

This is an API made using MLDB (Machine Learning Database) framework. All the functions implemented whithin MLDB are RESTful endpoints, 
which means that when we implement a function whithin MLDB framework, we are implementing an API that can be used by other 
applications (web application for example) to make predictions about food by sending as input an image URL. The script shows the full 
implementation, from taking the retrained model (graph file) to using the labels of food. The main function is called 'imageEmbedding', 
it takes a URL and makes a prediction using the retrained model. In the end of the script, I have included some examples of images
from the web where I used them to test my prediction function, the output of the function is shown in a form of an array where each label
has a value representing the probability of the food in the image being of type mentioned by that label.
