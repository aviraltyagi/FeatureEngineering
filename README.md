## FeatureEngineering

What is Data Preprocessing or Feature Engineering?

Data in its raw format is almost never suitable for use to train machine learning algorithms. Instead, data scientists devote a substantial amount of time to pre-process the variables to use them in machine learning. Feature engineering or Data Pre-processing is the process of using domain knowledge of the data to transform existing features or to create new variables from existing ones, for use in machine learning.

Why do we need Feature Engineering?
1) Some machine learning libraries do not support missing values or strings as inputs, for example Scikit-learn.
2) Some machine learning models make assumptions about the distributions of the variables, for example linear models.
3) Some machine learning models are sensitive to the magnitude of the features, for example linear models, SVMs and neural networks and all distance based algorithms like PCA and nearest neighbours.
4) Some algorithms are sensitive to outliers, for example linear models and adaboost
5) Some variables provide almost no information in their raw format, for example dates
