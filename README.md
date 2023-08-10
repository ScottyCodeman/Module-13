# Module-13

# Step 1: Prepare the data
* Using google Colab I imported the libraies I required mainly using `TensorFlow` and `Keras` to make the models for the data.
* I uploaded the csv and pulled it from the Resources folder, converted it to a DataFrame and droped the non relevant columns to binary classification
* Using `OneHotEncoder` I encoded a list of the categorical variables from the DataFrame, and then a list of the non-categorical variables
* split the data into tain and test data using `train_test_split` and then scaled the data using `StandardScaler`
