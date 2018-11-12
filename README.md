# mobile_price_classification
Comparison of five different classification algorithms to figure out the best one.
# To take a better look at the graphs in the notebook click on 
This code compares the accuracy of five different machine learning clasification algorithms trained on a [kaggle dataset](https://www.kaggle.com/iabhishekofficial/mobile-price-classification#test.csv) containing mobile price data. The code uses [scikit-learn](https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) to train these models on the procured dataset. 

**PROBLEM** : The problem here is to train the models on the train.csv dataset with price_range as the target label so that then the model can be used to classify the price_range of the data present in the test.csv file. 

**STEPS** : 
1. Download the .zip file containing the data to colab and unzip the file to fascilitate the data to be put into a pandas dataframe for analysis.
2. Take care of outliers, missing values and other descrepencies in the data that might have an adverse affect on the accuracy of the predictions.
3. Conduct Exploratory data analysis on the dataframe so that relationships can be understood between different labels and their relationships to the target label.
4. Train the models (Linear Regression, K-Nearest Neighbour, Logistic Regression, Decision tree, Random Forest) on the dataset so find out the accuracy score and find out the most accurate model for the problem.
5.  Use sklearn's classification_report function to display precision, recall, F1 score for the winning model.
6. Finally, use the winning model to predict the missing price_range in the test.csv file.
