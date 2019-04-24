Context
This Data was originally taken from Titanic: Machine Learning from Disaster .But its better refined and cleaned & some features have been self engineered typically for logistic regression . If you use this data for other models and benefit from it , I would be happy to receive your comments and improvements.
Content
There are two files namely:- train_data.csv :- Typically a data set of 792x16 . The survived column is your target variable (The output you want to predict).The parch & sibsb columns from the original data set has been replaced with a single column called Family size.

All Categorical data like Embarked , pclass have been re-encoded using the get_dummies method .

Additionally, 4 more columns have been added , re-engineered from the Name column to Title_1 to Title_4 signifying males & females depending on whether they were married or not .(Mr , Mrs ,Master,Miss). An additional analysis to see if Married or in other words people with social responsibilities had more survival instincts/or not & is the trend similar for both genders.

All missing values have been filled with a median of the column values . All real valued data columns have been normalized.

test_data.csv :- A data of 100x16 , for testing your model , The arrangement of test_data exactly matches the train_data

I am open to feedbacks & suggesstions
