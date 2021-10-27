# wifi_signal_machin_learning
The objective of this project is to predict the x,y coordination of customers by using given wifi strength data.

## Input data example:
![image](https://user-images.githubusercontent.com/40317107/139097424-0c5c1ec3-c945-4557-9fbc-9b4e179a70fe.png)

## Used ML Methods
Both Regression and Classification can be applied in this case
- Regression use x,y coordination as target
- MLP, XGboost(Multi ouput regression)
- Classification use location_coded as target
- XGBoost
- Random Forest
- Unsupervised Learning(Clustering) //For comparing purpose

## Expected result and Actual result of each model
![image](https://user-images.githubusercontent.com/40317107/139098832-c643df4f-8d8a-4351-b349-1313cff5f9fc.png)
![image](https://user-images.githubusercontent.com/40317107/139098884-3aeb8f52-8b65-4ea8-90a7-8a1aba6b10dd.png)
![image](https://user-images.githubusercontent.com/40317107/139098985-2868ce65-e144-414d-9b50-64fcdc32ab1e.png)

## Step 1: Load the dataset
![image](https://user-images.githubusercontent.com/40317107/139099709-f9a63f7b-3cb2-4117-8b10-446a938f89fc.png)
## Step 2: Preprocess the data
![image](https://user-images.githubusercontent.com/40317107/139099689-4dace1e0-1a1b-4130-87d8-2c36b8998587.png)
## Step 3: Split data into training and test set
![image](https://user-images.githubusercontent.com/40317107/139099241-f38ec6df-cd72-4600-933a-6b43af530d06.png)
## Step 4: Fit Random Forest Classifier and generate report
![image](https://user-images.githubusercontent.com/40317107/139099377-8f815992-26de-4f08-bdee-b2ee3cd23d9a.png)
![image](https://user-images.githubusercontent.com/40317107/139099619-6bc6efa7-a9ae-4523-a3d6-05e83a810b4e.png)
