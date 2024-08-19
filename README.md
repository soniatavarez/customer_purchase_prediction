# Customer Purchase Prediction: A Machine Learning Classification Project

This project was developed as part of my Data Mining class, with the objective of building a user interface that predicts whether a customer is likely to make a purchase based on user input. To achieve this, I implemented several supervised machine learning algorithms:

•	Naive Bayes

•	Decision Trees

•	Random Forests

•	Support Vector Machines (SVM)

•	K-Nearest Neighbors (KNN)


The primary goal is to evaluate the performance of each algorithm and determine which one best predicts customer purchase likelihood. After selecting the optimal model, a user interface was created to allow users to input data and receive a purchase likelihood prediction. **Click [here](https://soniatavarez.pythonanywhere.com/classification) to make a prediction with the model!** 

## Dataset
The dataset used in this project is the ["Predict Customer Purchase Behavior Dataset"](https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset) from Kaggle. It includes various customer information such as age, gender, product category, and loyalty program membership status.

## Project Steps
1.	**Data Loading and Exploration**: The dataset was loaded into a Pandas DataFrame, and exploratory data analysis was performed using Matplotlib and Seaborn to create visualizations.

2.	**Data Preparation**: The features (X) and target variable (Y) were separated, and the data was split into 70% training and 30% testing sets. The data was then standardized for better model performance.

3.	**Model Training and Evaluation**: Multiple machine learning algorithms were trained and tested. The model with the highest scores in the classification report was selected for deployment.
4.	**Model Deployment**:The selected model was saved into a pickle file and integrated into a user interface created using HTML and Python. The interface allows users to answer questions, and the model provides a prediction based on the input.
