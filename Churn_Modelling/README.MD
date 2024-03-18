<h3>Customer Churn Prediction using Artificial Neural Networks</h3>
This project focuses on predicting customer churn in a bank using artificial neural networks (ANNs). Customer churn refers to the phenomenon where customers stop doing business with a company. By predicting churn, companies can take proactive steps to retain customers and improve customer satisfaction.


<h4>Dataset</h4>
The dataset used in this project is the Churn_Modelling.csv file, which contains information about bank customers, including their credit score, geography, gender, age, tenure, balance, number of products, whether they have a credit card, whether they are active members, estimated salary, and whether they exited the bank.

<h4>Approach:</h4>

<h4>Data Preprocessing:</h4> The dataset is preprocessed to handle categorical variables (e.g., encoding) and scale the features.

<h4>Model Building:</h4> An ANN is built using TensorFlow and Keras. The model consists of three layers: two hidden layers with ReLU activation functions and an output layer with a sigmoid activation function.

<h4>Model Training:</h4> The model is trained on the preprocessed dataset using binary crossentropy as the loss function and the Adam optimizer.

<h4>Model Evaluation:</h4> The trained model is evaluated using the test set, and metrics such as accuracy are computed to assess its performance.

<h4>Prediction:</h4> The model is used to make predictions on new data points to determine whether a customer is likely to churn.

<h4>Conclusion</h4>
The ANN model achieved a certain level of accuracy in predicting customer churn. By using this model, banks can identify customers who are at risk of churning and take proactive measures to retain them, such as offering personalized incentives or improving customer service.

This project demonstrates the effectiveness of using ANNs for customer churn prediction and highlights the importance of data preprocessing and model evaluation in building successful predictive models.
