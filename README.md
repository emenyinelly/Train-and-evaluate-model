# Train-and-evaluate-model

munity
User woman1User man1User woman2User man2
+999

Back To My Project List
Implement Simple ML Algorithms in Python

Checkpoint 5: Train and evaluate model (Iris dataset)

Unlocked
What You're Aiming For
 Objective

Demonstrate your ability to train a supervised machine learning model and evaluate its performance using the classic Iris dataset.

 

 

Dataset

Iris dataset from sklearn.datasets

 
Contains measurements of iris flowers:

 
Features: sepal length, sepal width, petal length, petal width

 
Target: species of iris (Setosa, Versicolor, Virginica)

 

Instructions
Complete the following steps in Python (preferably in a Jupyter notebook or .py file). You may use scikit-learn, pandas, and matplotlib/seaborn for optional visualization.

 

 

 Steps to follow

Import the dataset

 
Load the Iris dataset from sklearn.datasets.load_iris()

 
Create a DataFrame using pandas (optional but helpful for inspection)

 
Explore the data

 
Print the shape, feature names, and target labels

 
Display a few rows of the data

 
Split the data

 
Use train_test_split() from sklearn.model_selection

 
Test size: 20% of the data

 
Use random_state=42 for reproducibility

 
Choose a model

 
Train a K-Nearest Neighbors (KNN) or Decision Tree Classifier

 
Fit the model on the training set

 
Make predictions

 
Use the model to predict on the test set

 
Evaluate performance

 
Print accuracy score

 
Show confusion matrix (optional: visualize with seaborn.heatmap)

 
Interpret: How well did the model classify each species?

 
 

 

 Bonus (Optional):

Visualize the decision boundaries (2D using only 2 features)

 
Try a second model (e.g., Logistic Regression) and compare results
