README - Regression Model in Keras - Final Project

----- Project Description -----
In this project I implemented a regression model using the knowledge of the IBM Introduction to Deep Learning & Neural Networks with Keras to predict continuous values. Several experiments are conducted to study and improve the model performance through techniques such as normalizing the input data, hyperparameter tuning and increasing model complexity.



----- File Content -----
1. Library import: numpy, pandas, sklearn, tensorflow.keras.

2. Functions used:
- load_data(file_path): Loads data from a local file or a URL.
- mean(scores): Calculates the mean of a list of errors.
- standard_deviation(scores): Calculates the standard deviation of the list of errors.
- report(experiment_label, avg_error_value, deviation_value): Generates a summary as a DataFrame.
- model_a(inputs=3): Creates a basic model with one hidden layer of 10 nodes.
- model_d(inputs=3): Creates a more complex model with three hidden layers of 10 nodes each.
- mean_squared_root_evaluation(trained_model, inputs, target, num_epochs=50, display_output=1): Trains the model and calculates the mean squared error (MSE).
- calculate_error_stats(inputs, target_values, model, iterations=50, epochs=50, verbose=0): Runs multiple iterations to obtain error statistics.

3. Procedure:
- Loading and validating the dataset.
- Splitting the dataset into training and testing sets.
- Model A with a baseline raw input model.
- Model B using normalized input features.
- Model C training the model with additional epochs.
- Model D valuating a model with three hidden layers.
- Final result comparison.



----- Requirements -----
1. Python 3.x
2. Libraries: numpy, pandas, scikit-learn, tLensorflow


----- How to Run the Project -----
1. Download the repository or download the ipynb file.
2. Add the concrete_data.csv file in the repository.
3. Run the file in a Jupyter Notebook enviroment (Google Collab, Visual, etc.)



----- Additional Notes -----
Modify the data file path if needed.


Author: Mauro Valls
Date: 2024
