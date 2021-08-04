
# To Predict Whether a song hits the Billboard or NOt?

A brief description :
   so basically our task is to predict whether a song will hit the 
   billboard or not by giving songs features to our machine
   learning model.

   we trained our data with Logistic regression algorithm.


## STEPS INVOLVED IN MODELLING:

1) Dropped the unnecessary columns
2) Balanced the output classes
3) scaled the data with min max scaler
4) splitted the datasets into train and test data(80/20)
5) Passed our preprocessed data into our logistic regression modela and
   Linear Discrimanant Analysis(LDA) and trained the data
6) We also performed hyperparameter tuning 

## Observations: (Logistic Regression)
1)ACCURACY:67

2)ROC:0.66

3)PRECISION: (70 FOR 0 AND, 65 FOR 1)

4)RECALL: (58 FOR 0 AND , 76 FOR 1)


## Observations (LDA):
1) ACCURACY:68

2) 2)ROC:0.67

3)PRECISION: (69 FOR 0 AND, 66 FOR 1)

4)RECALL: (60 FOR 0 AND , 75 FOR 1)

 
# Screenshots

## 1)logistic regression:

                  ROC_AUC CURVE:


  ![log auc1](https://user-images.githubusercontent.com/79806525/128175552-fad29948-a141-4a08-ae2d-0d35fae38b76.PNG)


                  CLASSIFICATION REPORT:

![LOG_CLASS2](https://user-images.githubusercontent.com/79806525/128176530-5c2313f4-bd85-42c2-a1cf-9ef67fade0df.PNG)


## 2)LDA:

                  ROC_AUC CURVE:

![LDA ROC1](https://user-images.githubusercontent.com/79806525/128176935-921bde12-324c-49f6-bb9b-52bc059aca64.PNG)


                  CLASSIFICATION REPORT:


![LDA CLASS2](https://user-images.githubusercontent.com/79806525/128177108-991a3a5e-2571-43b6-b653-61f4852bfcef.PNG)


