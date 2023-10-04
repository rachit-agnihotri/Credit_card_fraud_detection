# Credit_card_fraud_detection
This project focuses on predicting fraudalent transaction using different classification techniques. Given Dataset is highly biased.
### We can see that the data is totally biased most of the data is of non fraud values and having very less fraud values. We can deduce following points from it-->


*   The accuracy alone is not a good measure to check model so we will have to look for more measures.


*   Normal sampling technique will not work, either we will have to repeat data is this or have to use new sampling techniques

![image](https://github.com/rachit-agnihotri/Credit_card_fraud_detection/assets/114607757/7fd06ee5-d874-4175-9302-b80360f62712)

### There are 23 features available. Using describe feature from pandas we saw that the data is already normalized.
![image](https://github.com/rachit-agnihotri/Credit_card_fraud_detection/assets/114607757/fa93f799-a9dd-433c-a7d8-82bbef7e9822)
### Now as the data set is highly unbalanced we used different data sampling techniques which are as follows:-
*  Undersampling
*  Oversampling
*  Smote

### After it we used several classification techniques for classification. Some of them are:-
*  XGBoost
*  AdaBoost
*  Decision Tree
*  KNN
*  SVMC
  ![image](https://github.com/rachit-agnihotri/Credit_card_fraud_detection/assets/114607757/f52b968d-beda-49c6-a8e2-14cb9a1fc90b)
## Best results were obtained for XGBoost with oversampling
![image](https://github.com/rachit-agnihotri/Credit_card_fraud_detection/assets/114607757/e3d106ee-d2e9-4a21-bb6d-b128c5c24f72)
![image](https://github.com/rachit-agnihotri/Credit_card_fraud_detection/assets/114607757/b52536f6-9df8-45a1-b975-1beaf9d607fa)

