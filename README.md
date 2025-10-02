Install and import the required libraries
Load the data
Drop all rows with missing values , Data Granularity, Location selection
Create a function to map dates to seasons
Exercise 1: Map the dates to seasons and drop the Date column
Exercise 2. Define the feature and target dataframes
Exercise 3. How balanced are the classes?
Exercise 4. What can you conclude from these counts?
Exercise 5. Split data into training and test sets, ensuring target stratification
Define preprocessing transformers for numerical and categorical features
Exercise 6. Automatically detect numerical and categorical columns and assign them to separate numeric and categorical features
Define separate transformers for both feature types and combine them into a single preprocessing transformer
Exercise 7. Combine the transformers into a single preprocessing column transformer
Exercise 8. Create a pipeline by combining the preprocessing with a Random Forest classifier
Perform grid search cross-validation and fit the best model to the training data
Select a cross-validation method, ensuring target stratification during validation¶
Exercise 9. Instantiate and fit GridSearchCV to the pipeline
Exercise 10. Display your model's estimated score
Exercise 11. Get the model predictions from the grid search estimator on the unseen data
Exercise 12. Print the classification report
Exercise 14. Extract the feature importances
Exercise 15. Update the pipeline and the parameter grid
