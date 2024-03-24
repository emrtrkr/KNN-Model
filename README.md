The steps performed in this project are as follows:

Reading and cleaning the dataset: In the first step, the dataset (Anemia_Dataset.csv) is read and missing values (represented as NaN) are removed.

Identification of dependent and independent variables: Dependent and independent variables are extracted from the columns in the dataset. The independent variables are the features to be used in the prediction (e.g. blood parameters), while the dependent variable is the target variable to be predicted (anemia status).

Splitting the dataset into training and test sets: The data set is divided into training and test sets. The training set is used for learning the model, while the test set is used to evaluate the performance of the model.

Training the KNN model and calculating the accuracy value: The KNN model is trained on the training set and the performance of the model is evaluated on the test set. The performance of the model is measured by the accuracy value.

Determining the best K value: Hyperparameter optimization is performed to find the best K value for the KNN algorithm. This is done by creating KNN models for different K values and using cross-validation to determine the best K value.

Evaluating the performance of the model: The performance of the KNN model is evaluated using the accuracy value and the RMSE values calculated by cross-validation for different K values.

The main goal of the project is to predict whether a person has anemia or not, using specific features (blood parameters). This can be used in applications such as diagnostic support systems in the healthcare field and can help to determine the health status of individuals.
