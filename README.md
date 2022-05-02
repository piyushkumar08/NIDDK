# NIDDK EDA and Modelling

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

The dataset is collected from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. And the main objective is to build a classificaton model.

## 2. Installation <a name="installation"></a>

- Python - [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - impute (for fast_knn)
  - Scikit-learn
     - preprocessing (for MinMaxScaler) 
     - linear_model (for Logistic Regression)
     - model_selection (for train_test_split)
     - metrics (for classification_report and confusion_matrix)
     - neural_network (for MLPClassifier)
     - neighbors (for KNeighborsClassifier)
     - svm 
     - tree (for DecisionTreeClassifier0
     - ensemble (for Random Forest and Ada boost) 
     - naive_bayes 
     - discriminant_analysis (for QDA)
     - gaussian_process (for Gaussian Process Classifier and RBF)
  - imblearn (for over_sampling.SMOTE)
  - scikitplot

  
## 3. Data<a name="data"></a> 

collected from the [National Institute of Diabetes and Digestive and Kidney Diseases](https://repository.niddk.nih.gov/home/)
Also uploaded above by the name : ["NIDDK dataset.csv"](https://github.com/piyushkumar08/NIDDK/blob/main/Dataset/NIDDK%20dataset.csv)


## 4. Implementation <a name="model"></a> 
  - Missing value treatment using KNN
  - Data scaling using MinMaxScaler
  - Oversampling using SMOTE (to resolve the data imbalancement issue)
  - Extensive Exploratory Data Analysis
  - Fitting the data on various models and comparing the accuracy
  - Plotting the ROC curve for better comparison

## 5. Result<a name="results"></a>
For the classification, RBF SVM is performing the best with the accuracty score 85 and Gaussian Process is also close with 84.5 accuracy score.

The details of the results are shown in the jupyter notebook itself along the source code. Click here to see the result -> [Result](https://github.com/piyushkumar08/NIDDK/blob/main/NIDDK.ipynb) 
