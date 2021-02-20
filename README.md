# NLP

Objective of this project:
1. Extract Personal Identification Information like:

    1. Name
    2. SSN
    3. Phone
    4. Plate Number
    5. Address
    6. Credit Card Number

2. Predict the Label/ category of the extracted PII 


Usage:
1. Download the zip and install the dependencies provided in Requirements.txt
2. Run Extraction.ipynb - which contains the logic to extract required information. Extraction is done using NER, and LexNLP in combination with regex
3. Run Predictions.ipynb - has been built using Multinomial Naive Bayes
4. Result is stored in Prediction.xlsx


Data:
1. PII_Train_Large_Data_Test_Data.xlsx - Contains train and test data
2. Test.xlsx - Contains extracted information
3. Prediction.xlsx - Contains predicted labels


Accuracy: 83.68%
