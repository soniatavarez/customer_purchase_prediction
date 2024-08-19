# Customer Purchase Prediction: A Machine Learning Classification Project

This project was developed as part of my Data Mining class, with the objective of building a website that predicts whether a customer is likely to make a purchase. To achieve this, I implemented several supervised machine learning algorithms:

•	Naive Bayes

•	Decision Trees

•	Random Forests

•	Support Vector Machines (SVM)

•	K-Nearest Neighbors (KNN)


The primary goal is to evaluate the performance of each algorithm and determine which one best predicts customer purchase likelihood. After selecting the optimal model, a website was created to allow users to answer questions and receive a purchase likelihood prediction. **Click [here](https://soniatavarez.pythonanywhere.com/classification) to make a prediction with the model!** 

## Dataset
The dataset used in this project is the ["Predict Customer Purchase Behavior Dataset"](https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset) from Kaggle. It includes various customer information such as age, gender, product category, and loyalty program membership status.

## Project Steps
1.	**Data Loading and Exploration**: The dataset was loaded into a Pandas DataFrame, and exploratory data analysis was performed using Matplotlib and Seaborn to create visualizations.

2.	**Data Preparation**: The features (X) and target variable (Y) were separated, and the data was split into 70% training and 30% testing sets. The data was then standardized for better model performance.

3.	**Model Training and Evaluation**: Multiple machine learning algorithms were trained and tested. The model with the highest scores in the classification report was selected for deployment.

4.	**Model Deployment**:The selected model was saved into a pickle file and integrated into website using HTML and Python. The website allows users to answer questions, and the model provides a prediction based on the input.

## Visualizations 

The graph displays the accuracy, precision, recall, and F1-scores for all the classifiers used. These are all methods used to evaulate performance. The Random Forest model yielded the best performance.
<img width="1307" alt="algorithms" src="https://github.com/user-attachments/assets/c0061e47-aa58-4420-a614-dda4b48f1545">

The dataset was imbalanced, with more data under "purchase not made" compared to "purchase made." To address this, the dataset was adjusted to include a subset of 600 samples per category.

<img width="356" alt="groups_v1" src="https://github.com/user-attachments/assets/6838d35c-0268-433d-a619-c631af98102b">
<img width="356" alt="groups_v2" src="https://github.com/user-attachments/assets/9dd024e7-f0af-484f-a5e7-e8c9648f3abf">

A correlation heatmap was generated to identify the relationships between variables in the dataset. The strongest correlations were observed between purchase likelihood and features such as time spent on the website, loyalty program membership, age, and discount availability.

<img width="746" alt="correlation_map" src="https://github.com/user-attachments/assets/b29cf2ed-843d-4e8a-8791-073f3965f043">

Given that loyalty membership status had the highest correlation with purchase status, a boxplot was created to explore the relationship between the number of purchases made and loyalty membership status. The plot indicates that loyalty members tend to shop slightly more than non-loyalty members.

<img width="769" alt="membership_status" src="https://github.com/user-attachments/assets/d25ea755-197b-46f5-b8c1-d7e097626041">






