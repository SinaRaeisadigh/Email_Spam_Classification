# Email_Spam_Classification

The project showcases multiple popular machine learning models and compares their performance on a text classification problem. It uses a typical machine learning pipeline that includes data preprocessing, feature extraction, model training, and evaluation.

Here's an overview of the key sections and the approach used in the notebook:

## 1. Libraries and Data Preparation
The notebook begins by importing essential libraries, like pandas, numpy, sklearn, etc.
The dataset used for spam classification is loaded, and data cleaning and preprocessing are conducted. This includes tokenization and transforming text data into numerical features using approaches like TF-IDF (Term Frequency-Inverse Document Frequency).

## 2. Data Vectorization
Textual data is converted into numerical form using vectorizers such as CountVectorizer or TF-IDF Vectorizer. This transformation is crucial to make the data compatible with machine learning models.

## 3. Splitting the Data
The data is split into training and testing sets using train_test_split to ensure the models can be evaluated on unseen data.

## 4. Model Training and Evaluation
Several classification models are used to predict whether an email is spam or not. The models explored include:
Naive Bayes Classifier (MultinomialNB): This model achieved an accuracy score of around 94.43%.
Support Vector Machine (SVM) (SVC): The notebook used a radial basis function kernel (rbf). The accuracy achieved was 89.95%.
Random Forest Classifier (RandomForestClassifier): This ensemble-based model yielded an accuracy of 96.06%, which seems to be the highest among all models used.

## 5. Observations on Accuracy
The notebook compared multiple models to determine the best-performing one for this classification task.
The Random Forest Classifier had the highest accuracy, followed by Naive Bayes. This suggests that Random Forest's ability to handle non-linearity and capture more complex relationships makes it very effective for spam classification.
