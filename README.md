# Iris Classification

This project performs classification on the famous Iris flower dataset using a Decision Tree Classifier. The Iris dataset is widely used for pattern recognition tasks and is simple yet excellent for beginners in machine learning.

## Dataset
The dataset used is from this GitHub repository (IRIS_CSV.csv).
It contains 150 samples with the following features:
    sepallength (cm)
    sepalwidth (cm)
    petallength (cm)
    petalwidth (cm)
    class (species: Iris-setosa, Iris-versicolor, Iris-virginica)

There are no missing values, and all features are numeric except the class label.

## Steps Performed

**Data Loading**
The dataset was read using pandas.read_csv().

**Data Exploration**
Displayed dataset structure using .info() and .describe().
Checked for missing values.
Grouped data by class labels to verify class distribution.

**Data Visualization**
Created box plots for each feature grouped by class using seaborn to understand feature distributions.

**Data Preparation**
Features (x) and labels (y) were separated.
Split into training and testing sets (67% training, 33% testing) using train_test_split() with a random state of 42.

**Model Training**
Used a DecisionTreeClassifier from sklearn to train on the training set.

**Model Evaluation**
Predicted the labels for the test set.
Evaluated the model using accuracy_score.
Achieved an accuracy of 98% on the test data.

## Libraries Used
- pandas
- seaborn
- matplotlib
- scikit-learn

## Conclusion
The Decision Tree Classifier performed excellently on the Iris dataset, achieving an accuracy of 98%. Data visualization helped in understanding feature distributions across classes, aiding in effective model training.
