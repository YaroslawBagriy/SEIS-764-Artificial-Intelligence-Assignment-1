# SEIS-764-Artificial-Intelligence-Assignment-1
This is the solution for the first assignment for class SEIS 764 Artificial Intelligence

1. Load the dataset and print how many data instances and columns we have.
2. Print if there are any missing values in any of the columns.
3. Print any duplicate rows and delete them if they are available.
4. Split the data into the features (i.e. X) and the target (i.e. y). Print first few rows of X and y.
5. Split the dataset into training (70%) and testing (validation) set (30%). Perform normalization of the data using
standardization.
6. Print how many data instances and columns we have in the train set.
7. Build a simple NN Regression model that has one layer and one unit. Specify mean_squared_error for the loss
and adam for optimizer. Run it for 100 epochs. Plot the loss plot for training and validation. You can do that like
this: r = model.fit(X_train, y_train, validation_data=(X_test, y_test), epochs=100)
8. Next, change the optimizer to sgd. Run it for 100 epochs. Plot the loss plot for training and validation.
9. Now, change the optimizer to rmsprop. Run it for 100 epochs. Plot the loss plot for training and validation.
10. Which network performed the best? Do you have ideas on how the performance can be improved? Answer this
question in the markdown cell in the notebook.
