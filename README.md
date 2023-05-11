# 🚗 Car Price Prediction using Linear Regression 🚗
Hello Everyone, 👋

In this repository, I aim to predict the value of a car based on various features such as the engine size, horsepower, and other features. I used linear regression model to make the prediction and then calculate the accurecy of the model.

## Requirements
The following libraries are required to run the code:
* numpy
* pandas
* matplotlib
* seaborn
* sklearn

## Dataset
The data used for this project is the Car Dataset . The data includes information on different makes and models of cars and their characteristics , 

📍 Link of the Dataset : (https://www.kaggle.com/datasets/krishnasyenugula/automobile-data)

## Steps involved in the Project
### 1️⃣ Data Cleansing

   #### * Dealing with nulls
         I filled the intger null values with mean of its column.

   #### * Data Correletion
         I made correletion on data to know the degree relationships between features and determine if this relationship is direct or reverse 
         and this will help in feature reduction by distinguishing the important features to depend on it in training step.

   #### * Categorical Features transformation
         I turned all categorical features to numerical one to facilitate training model 

   ### 2️⃣ Divide data 
         First , I divide data into Features & Labels , and then divide it into train & test with test size 20% 

   ### 3️⃣ Numerical Feature Scaling
         I scaled data to minimize Bios and prevent outliers between the features.

   ### 4️⃣ Apply Linear Regression 
         I applied Linear Regression model to the data after training it to pridect the price of cars.

   ### 5️⃣ Evaluate the model
         I made this by using mean absolute error and root mean squared error to calculate the accuracy of the model 

   ### 6️⃣ Inverse Transformation of scaling
         This step is very important to know the actual price predicted . 



