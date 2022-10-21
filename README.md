# Predicting Sales for Food Items at Various Stores
## Steven Phillips
### Business Problem:
The problem explored in this project is to discover which of several features increase the sales at various stores.
### Data:
The data used for this project originates from:
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/
The data items include several features including: item weights, item visibility, outlet types, outlet sizes, fat content and MRP.
## Methods
The data were prepared by eliminating duplicates and focusing on Item Weight, Item Visibility, MRP, Fat Content, and Outlet Location Type.  Outlet Establighment Year, Item Identifier, and Outlet Identifier were not included in the analysis or modeling, as they do not provide additional insights.
## Results 
This first image showcases the correlations between the numeric variables.
![image](https://user-images.githubusercontent.com/113748627/197235260-0b79b8f4-9f22-402d-9a50-14910e556440.png)
This next image showcases the distribution of the Item Weights, which have a high number near 12 ounces.
![image](https://user-images.githubusercontent.com/113748627/197235403-b45cc51e-cf7c-4977-bdf5-857b5d29df2d.png)

## Model
The model chosen is a Decision Tree Model with a depth of 5.
The metrics for evaluation of our optimized Decision Tree Model of depth 5 on our test data are: Mean Absolute Error(MAE) 738.32, Mean Squared Error(MSE) 1,118,185.97, and Root Mean Squared Errer(RMSE) of 1,057.44. The R2 value explaining the variability in our target data is 0.5947.
## Recommendations
The R2 score of our model is 0.5957, explaining 59.47 percent of the variability in our target data.
## Limitations & Next Steps
This R2 score is not ideal, but was the highest of the models explored.  Additional data should be gathered on additional feautures that may provide more accurate predictions.
### For further information
For any additional questions, please contact me above.
