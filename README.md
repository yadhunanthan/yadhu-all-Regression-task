Step 1: Collect Data X = features (inputs) y = target (continuous value you want to predict) Example: Netflix - open close

Step 2: Split Data Divided data into: Training set (to train the model) testing set (to check performance)

step 3: Create the Model Use a Decision Tree Regressor: from sklearn.tree import from sklearn.svm import SVR SupportVectorRegression ()

Step 4: Train the Model Teach the Model using training data: model.fit(X_train, y_train)

Step 5: Make Predictions Use the trained model to predict new values: y_pred = model.predict(X_test)

Step 6: mse=mean_squared_error(y_test,svr_prediction) mse Accuracy:28.955955412556694

