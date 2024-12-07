Heart-Failure-Prediction

Using the dataset for heart disease and ECG parameters that can help predict it, we are going to analyze relations between each parameter and the heart failure risk to develop a risk assessment model for a life insurance company. This will allow the company to request ECG results from potential clients in the risk zone and analyze them to calculate the risk. The risk rating in turn will aloow the company to include it in their pricing model, and provide more accurate and better suited quotes for individual clients.

We start our analysis with cleaning the data and understanding each parameter in the dataset. We learned the meaning and normal values for each parameter, determined which parameters have 0 values.

Using a KNN classification model, we determined if the parameters included in the dataset are enough to build a reliable prediction model for the heart disease. In KNN classification notebook we have built the classification model and determined it's accuracy. With accuracy above 80%, we can state that the parameters inlcuded are enough to predict heart failure risk. The model can be used by the insurance company to determine if the client  has heart disease currently, and use that information in the pricing mechanism.

Moving forward, we created a logistic regression model to determine a heart failure risk based on the features provided. We also used a linear regression model to determine dependencies between each feature and a heart failure risk. This method proved inefficient with our dataset, as the data plots are very scattered and do not showcase a clear linear relationship between any feature and the heart failure risk. Feature distributions differ from normal, the relationships are complex and involve multiple parameters. This is a normal situation with medical data, as diseases are caused by many factors and there are other correlations between parameters themselves. This method allowed us to see some basic relationships between features and heart failure risk, understand our data better.

Finally, we used a model to determine permutation importance and feature importance more accurately. This method helped us showcase influence of each parameter more clearly.


In a conclusion, we can use KNN classification model to determine a heart disease present for each client. We also learned a lot about our dataset and the dependencies between each feature and disease prediction. This information allows us to build a machine learning model that will predict heart failure risk more accurately.

Moving on, we have optimized the KNN model for the best accuracy and F1 score. We improved accuracy from 85% to 90% using elbow method to find optimal K value, select optimal pre-processing method and distance metric. 

From there, we took another step to try and improve the model's accuracy. We experimented with DNN model to achieve better performance than in KNN model.


Video reports:

Maksym Parkhomchuk: https://drive.google.com/file/d/1tdKUNfdpGg3xkXW0lAYyGAmElxdkyIQ5/view?usp=sharing

