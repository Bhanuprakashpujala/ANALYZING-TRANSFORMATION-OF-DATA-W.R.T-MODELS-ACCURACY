# ANALYZING-TRANSFORMATION-OF-DATA-W.R.T-MODELS-ACCURACY
STEP 1: Load the (TITANIC)  Dataset from the seaborn Library.
STEP2: Data Cleaning (Missing value Treatment, Duplicates Handling )
STEP3: Copy the dataset to new variable called TitanicTransformed
Step4: Split both datasets into train and tests
STEP5: Data Preprocessing for TitanicTransformed with Transformation of continuous Data, Nominal and Ordinal Categorical Data And
STEP6: Build a model using Decision Tree and Logistic Regression 
STEP 7:Test the Model and 
 STEP8:Find the Score of models by Evaluation Metrics like Accuracy and Confusion Matrix
STEP9: Now Do Data Preprocessing for Orginal_Dataset  without transformation of continuous Data, Nominal and Ordinal Categorical Data 
STEP10 : Follow the same steps as TitanicTransformed (step-4,5,6)
STEP11: Justify which Dataframe got the High Score with Explanation

conclusion :
Logistic Regression:
Before transformation and scaling: The accuracy was 0.818 on train data and 0.772 on test data. The confusion matrix for the test data was [[124, 20], [35, 71]].

After transformation and scaling: The accuracy improved slightly to 0.821 on train data and 0.780 on test data. The confusion matrix for the test data was [[124, 20], [35, 71]].

Insights: In this case the improvement in accuracy after transformation and scaling was not significant. This suggests that the logistic regression model may not be very sensitive to the scaling and transformation of the data.
Decision Tree:
Before transformation and scaling: The accuracy was 0.985 on train data and 0.748 on test data. The confusion matrix for the test data was [[118, 26], [37, 69]].

After transformation and scaling: The accuracy on the train data remained the same at 0.985, while the accuracy on the test data decreased slightly to 0.720. The confusion matrix for the test data was [[111, 33], [37, 69]].

Insights: In this case, the accuracy on the train data remained the same after transformation and scaling, while the accuracy on the test data decreased slightly. This suggests that the decision tree model may be sensitive to the scaling and transformation of the data.
Comparing the results, it seems that the decision tree model performed better than the logistic regression model. The decision tree model had higher accuracy on both the train and test datasets after transformation and scaling, whereas the logistic regression model had only a slight increase in accuracy after transformation and scaling.

This could be because decision trees are able to capture more complex relationships between the input features and the target variable compared to logistic regression. Additionally, decision trees are non-linear models and are able to handle non-linear relationships in the data, while logistic regression assumes a linear relationship
