# CNC Milling Tool (Tool Wear Detection)
## Project Overview
### Project Details
In this project machining data was collected from a CNC machine for variations of tool condition, feed rate, and clamping pressure.

In 18 machining experiments, time series data was collected with a sampling rate of 100 ms from the 4 motors in the CNC (X, Y, Z axes and spindle).
### Goal
The main goal of the project is to find the best model to predict the machine failure.
## Tools:
### Models:
- Machine Learning: LogisticRegression, SVC, RandomForest, GradientBossting, KNN (scikit-learn)
- Deep Learning: ANN(TensorFlow)
### Data Visualization:
- Matplotlib
- Seaborn
### Data Preprocessing:
- Missing Data Imputation: ArbitraryNumberImputer, EndTailImputerm, RandomSampleImputer
- Feature Scaling: StandardScaler, RobustScaler, MinMaxScaler
- Feature Selection: DropConstantFeatures, DropDuplicateFeatures, DropCorrelatedFeatures
### Metrics:
- Accuracy
- Roc-auc
- Recall
- Precision
- F1
- Confusion matrix
### Other:
- Grid Search (hyperparameters tuning)
- Pipeline
- Pandas
- Numpy
