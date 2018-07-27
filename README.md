# Item-Based-Collaborative-Filtering

The project implements the item based collaborative filtering system which is a neighbourhood based approach to recommend items to a user. It uses the MovieLens dataset which contains 1 million ratings and then evaluates the predictions on various evaluation measures. The method used for calculation of similarity of users is adjusted cosine similarity. Then the predicted ratings that any user will give an item is calculated with the weighted sum formula with the help of the similarity matrix that was calculated in the previous step. The evaluation measures that were used are as follows:-

1.Mean Absolute Error(MAE)
2.Root Mean Squared Error (RMSE)
3.Good Item MAE (GIM)
4.Good Predicted Item MAE(GPIM)
