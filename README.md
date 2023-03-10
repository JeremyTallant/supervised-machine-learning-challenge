# Supervised Machine Learning Challenge
![1728957](https://user-images.githubusercontent.com/112406455/218812823-db27c5fb-45de-4d86-8870-07f5199a369c.jpg)

## Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Instructions

### Retrieve the Data
The data is located in the Challenge Files Folder:

* `lending_data.csv`

Import the data using Pandas. Display the resulting dataframe to confirm the import was successful.

<img width="1214" alt="Screenshot 2023-02-14 at 11 30 43 AM" src="https://user-images.githubusercontent.com/112406455/218813436-bd012793-20e7-4419-8eb9-fefb456b9f6f.png">


### Predict Model Performance
You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct!

Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.

<img width="1214" alt="Screenshot 2023-02-14 at 11 20 16 AM" src="https://user-images.githubusercontent.com/112406455/218813877-312da1ef-f47c-4aef-adb1-b8256384c612.png">

### Split the Data into Training and Testing Sets
Create the features DataFrame, `X`, by removing the `loan_status` column. Create `y`, the labels set, by using the `loan_status` column. Split the data into training and testing datasets by using the `train_test_split` function.

<img width="1214" alt="Screenshot 2023-02-14 at 11 20 26 AM" src="https://user-images.githubusercontent.com/112406455/218814155-ec2b19eb-f844-42eb-88a8-c0583291fb58.png">


### Create, Fit and Compare Models
Create a Logistic Regression model, fit it to the training data that you created in the previous step. Then, determine the model's score by using the `score` function and the testing data from the previous step. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like.

Logistic Regression Model:

<img width="1214" alt="Screenshot 2023-02-14 at 11 20 38 AM" src="https://user-images.githubusercontent.com/112406455/218814709-a09d2f96-c663-48a7-8cf2-d443c4d1b26d.png">

Random Forest Classifier Model:

<img width="1214" alt="Screenshot 2023-02-14 at 11 20 51 AM" src="https://user-images.githubusercontent.com/112406455/218814936-17654813-6270-46d2-a364-ed01e6efe98b.png">


Review the scores of each model. Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the designated markdown cell.

<img width="1213" alt="Screenshot 2023-02-14 at 11 20 43 AM" src="https://user-images.githubusercontent.com/112406455/218815089-9b31f740-c3f2-4cf9-ba85-8b0d1cdc044c.png">

## References
Loan Approval Dataset (2022). Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

