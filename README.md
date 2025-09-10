# USA REAL ESTATE
This is capstone assignment and here is link to the notebook - https://github.com/Mawitey/CapstoneAssignment/blob/main/Capstone%20Assignment.ipynb

###  Problem statement
The primary objective of this project is to perform a comprehensive exploratory data analysis (EDA) on a real estate dataset. This is done to understand the underlying patterns and relationships between variables such as house price, size, and location. Following the EDA, a baseline machine learning model is developed to provide a starting point for more complex predictive modeling, allowing for a clear evaluation of future model improvements.



### Results
A Logistic Regression model was selected and trained to serve as the baseline for this project. The model's performance on the test data was evaluated using several metrics:
#### Overall Accuracy: 
The model achieved an accuracy of approximately 59%.
#### Detailed Metrics: 
A classification report provided a breakdown of the model's precision, recall, and F1-score for each price_category, offering a more granular view of its performance.
#### Confusion Matrix: 
A confusion matrix was generated to visualize the model's predictions and identify where it was making correct and incorrect classifications.



### Findings
Through the EDA process, several key insights were discovered:
#### Data Quality: 
The initial dataset contained missing values that required cleaning. These were handled by removing the affected rows to ensure the integrity of the analysis.
#### Feature Distribution: 
Visualizations, including histograms, showed the distribution of key features like price, house_size, and the number of bedrooms and bathrooms. These distributions revealed the typical ranges for these variables within the dataset.
#### Correlations: 
Correlation analysis helped identify the strongest relationships between features. The bar chart showing correlations with price revealed which variables have the most significant linear relationship with the target variable.
#### Data Preparation: 
A new feature, price_category, was engineered from the continuous price variable to prepare the data for a classification task. Categorical features were also encoded, and numerical features were scaled to ensure proper model training.



### Next steps
This project successfully establishes a solid foundation for future work. Potential next steps to improve the model's performance include:
#### Advanced Modeling: 
Experimenting with more sophisticated machine learning models, such as DecisionTree, k-nearest neigbours, or SVM, which may better capture complex, non-linear relationships in the data.
#### Hyperparameter Tuning: 
Systematically tuning the hyperparameters of the chosen model to find the optimal configuration that maximizes performance.

