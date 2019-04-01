# Intro to Machine Learning
Machine Learning Algorithms from the Udacity Intro to Machine Learning Nanodegree


## Data sets and Questions 

The Enron fraud is a big, messy and totally fascinating story about corporate malfeasance of nearly every imaginable type. The Enron email and financial datasets are also big, messy treasure troves of information, which become much more useful once you know your way around them a bit. Find out about the Enron data set in the [`explore_enron_data`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/explore_enron_data.ipynb) Jupyter Notebook. 

### Enron story

* The largest case of corporate fraud in American history: the Enron Corpus with real emails
* Use it to to try to figure out if there are patterns within the emails of people who were persons of interest in the fraud case to see if you can identify those patterns
* Using regressions: understand the relationship between the salaries of the people in Enron and their bonuses
* Clustering on the data (type of unsupervised learning): who within this organization was a member of the board of directors and who was just a regular employee
  * Example: in netflix they use it to identify particular types of people by their movie choices (clusters of users)
* Outlier detection and removal to find certain lines in the data set that were bugs basically, clean out manually

#### Person of Interest (POI) - Target
* Indicted
* Settled without admitting guilt
* Testified in exchange for immunity

## Regression

Model continuous data using linear regression and use regression to predict financial data for Enron employees and associates in the [`regressions_enron_data`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/regressions_enron_data.ipynb) Jupyter Notebook. 

## Outliers
Outlier detection and removal in the [`enron_outliers`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_outliers.ipynb) Jupyter Notebook. 

### #1 Outliers - Rejection Algorithm

* Fit a regression, take 10% of points that have the largest residuals, relative to your regression
* Remove them
* Re-train

### #2 Outliers in the Enron finance data

* get acquainted with some of the outliers in the Enron finance data
* learn if/how to remove them.

## Clustering - Unsupervised Learning

Learn about what unsupervised learning is and find out how to use scikit-learn's k-means algorithm in the [`enron_clustering`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_clustering.ipynb) Jupyter Notebook. 

## Feature Scaling

Apply `MinMaxScaler` on the `salary` and `exercised_stock_options` features from the Enron dataset in the previous [`enron_clustering`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_clustering.ipynb) Jupyter Notebook ro make better predictions abou POIs.

## Text Learning

Find out how to use text data in your machine learning algorithm. Use sklearn `TfidfVectorizer` to convert a collection of raw documents to a matrix of TF-IDF features. Check it out in the [`enron_text_learning`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_text_learning.ipynb) Jupyter Notebook.

## Feature Selection

When and why to use feature selection using sklearn classifier `feature_importances_` attribute to find out outliers in text data in the [`enron_feature_selection`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_feature_selection.ipynb) Jupyter Notebook.

## Principal Component Analysis (PCA)
Learn about data dimensionality and reducing the number of dimensions with principal component analysis (PCA) in the [`eigenfaces`](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/eigenfaces.ipynb) Jupyter Notebook, an example that follows Faces recognition using eigenfaces and SVMs.

## Cross-Validation
Learn more about testing, training, cross validation and parameter grid searches in the [enron_validation](https://github.com/AnaHristian/intro_to_machine_learning/blob/master/enron_validation.ipynb) Jupyter Notebook
