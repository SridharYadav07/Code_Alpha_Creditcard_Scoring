# Code_Alpha_Creditcard_Scoring
This project performs a complete end-to-end machine learning process on the "UCI Credit Card" dataset to predict the likelihood of a person defaulting on their credit card payment in the next month.
It uses the Random Forest Classifier, a popular machine learning algorithm, for prediction and evaluates its performance using various metrics like accuracy, confusion matrix, classification report, and ROC-AUC score.

Tools Used:
Pandas: For data manipulation and preprocessing. It is used to load the dataset, perform data cleaning (like dropping unncessary columns, mapping categorical values), and handle missing values.

NumPy: Used for numerical operations (although its usage is limited in this code).
Scikit-learn (sklearn): For data splitting, model training, and evaluation:
LabelEncoder: To encode categorical varibales such as 'SEX' into numerical values.
StandardScaler: To standardize numerical features to have a mean of 0 and a standard deviation of 1.
train_test_split: To divide the data into training and test sets.
RandomforestClassifier: The Random Forest algorithm is used to train a model for predicting credit card defaulst.
Evaluation functions: accuracy_score, confusion_matrix, classification_report, and roc_auc_score are used to assess the performance of the trained model. 
Matplotlib and Seaborn: For data visualization, Seaborn is used to plot the confusion matrix, and Matplotlib is used to display the plot.
