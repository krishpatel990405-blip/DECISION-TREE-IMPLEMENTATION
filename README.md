# DECISION-TREE-IMPLEMENTATION

*COMPANY* : CODTECH IT SOLUTIONS 

*NAME* : PATEL KRISHKUMAR VASANTBHAI

*INTERN ID* : CTIS9788

*DOMAIN* : MACHINE LEARNING 

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

## This project demonstrates the implementation of a Decision Tree Classification model using the Titanic dataset to predict passenger survival. The objective of the project is to apply data preprocessing, feature engineering, model training, evaluation, and pruning techniques to build an accurate and interpretable machine learning model.

## The project begins by importing essential Python libraries such as Pandas, Seaborn, Matplotlib, and Scikit-learn. The Titanic dataset is loaded using Seaborn and explored through functions like head(), describe(), info(), and isnull().sum(). This exploratory analysis helps in understanding the structure of the dataset, identifying missing values, and selecting appropriate features for model training.

## Five important features are chosen for prediction: passenger class (pclass), gender (sex), fare (fare), embarkation port (embarked), and age (age). The target variable is survived, which indicates whether a passenger survived the Titanic disaster. Before training the model, data preprocessing is performed to handle missing values. The SimpleImputer class is used to replace missing values in the age column with the median age and missing values in the embarked column with the most frequent category. This ensures that the dataset contains no null values that could negatively affect model performance.

## Since machine learning algorithms require numerical input, categorical features are encoded using the LabelEncoder class. The gender and embarkation columns are converted into numerical values, making them suitable for model training. After preprocessing, the dataset is divided into training and testing sets using the train_test_split() function, where 80% of the data is used for training and 20% for testing.

## A Decision Tree Classifier is then created and trained on the training data. The model learns decision rules based on the selected features to classify passengers as survived or not survived. The trained model is evaluated on the test dataset using the accuracy_score() metric, which measures the proportion of correctly classified instances.

## To improve model interpretability, the decision tree is visualized using the plot_tree() function from Scikit-learn. The visualization displays decision nodes, feature splits, class labels, and predicted outcomes, providing a clear understanding of how the model makes decisions.

## The project further applies Cost Complexity Pruning to reduce overfitting and create a more generalized model. The cost_complexity_pruning_path() method is used to obtain different values of ccp_alpha, which control the pruning process. Multiple decision trees are trained using different alpha values, and their performance is evaluated on the test set. The alpha value that produces the highest accuracy is selected as the optimal pruning parameter.

## Finally, a pruned Decision Tree model is trained using the best alpha value. The pruned model is visualized and saved as image files in PNG and JPG formats. The final accuracy of the optimized model is calculated and compared with the original model. Overall, this project demonstrates the complete workflow of building, evaluating, visualizing, and optimizing a Decision Tree Classifier using the Titanic dataset, highlighting the importance of data preprocessing, model evaluation, and pruning techniques in machine learning.


## FINAL OUTPUT :

<img width="1039" height="495" alt="Image" src="https://github.com/user-attachments/assets/7d86168a-e637-4709-b217-cac90428c7d5" />
