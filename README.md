# ComputerVirus
Trained different Machine Learning Models on data.


Conclusion

1) We did not perform normalization of the data which could improve the performance of the model as it would make every datapoint have the same scale so each feature is equally important.

2) We did not derive additional features from the existing features which could be more predictive and further improve the model's performance for both Random Forest and XGB.

3) We could have tried additional methods to further reduce the overfitting in the Random Forest model by specifying another tuning parmater, min_samples_leaf and setting a larger value for range of values to be tuned

In summary, XGBoost is better at identifying the virus classes as it correctly identified than other models.

I has been also observed that due to more occurrance of '2' and '3' targets most predictions are done for those categories.
