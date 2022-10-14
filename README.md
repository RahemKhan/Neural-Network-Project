## A comparative study in diagnosing Diabetes through Multilayer Perceptron and Support Vector Machine
* Integrated two classifiers (MLP and SVC) to the diabetes dataset and formed a comparasion.
* Tuned the moodels hyperparameters via grid search and 10-fold cross validation.
* The best MLP model had an accuracy of 0.74.
* The best SVC model had an accuracy of 0.76.

### Packages
* Python Version: 3.8.3

* Packages used:

* joblib==0.16.0
* matplotlib==3.2.2
* numpy==1.18.5
* pandas==1.0.5
* scikit-learn==0.23.1
* scipy==1.5.0
* seaborn==0.10.1
* skorch==0.9.0
* torch==1.7.1

### Dataset
The dataset was originally downloaded from Kaggle - https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### Data Transformation
* Dummy encoding has been applied on categorical features
* Split the dataset into training and test sets (80% and 20%)

### Hyperparameters 

#### MLP:
* learning_rate=0.1
* momentum=0.90
* hidden_size=200

#### SVM:
* C=0.1
* degree=2
* kernel=poly

### Best Models 

![image](https://user-images.githubusercontent.com/92123173/195879292-7c0b921e-5d47-40c9-9bc9-d0a03468af00.png)




