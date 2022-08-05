# feature-scaling

Feature scaling is the process of normalising the range of features in a dataset.

Real-world datasets often contain features that are varying in degrees of magnitude, range and units. Therefore, in order for machine learning models to interpret these features on the same scale, we have to perform feature scaling.

In science, we all know the importance of comparing apples to apples and yet many people, especially beginners, have a tendency to overlook feature scaling as part of the preprocessing steps for machine learning. This has proven to cause models to make inaccurate predictions.

In this notebook, we will discuss why feature scaling is important, the difference between normalisation and standardisation as well as how feature scaling affects model accuracy. More specifically, we will explore the applications of 3 different types of scalers in the Scikit-learn library:

1. MinMaxScaler
2. StandardScaler
3. RobustScaler.
