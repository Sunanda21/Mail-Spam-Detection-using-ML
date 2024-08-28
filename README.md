# Mail-Spam-Detection-using-ML
Mail spam detection using a Logistic Regression model involves transforming email text into numerical features using methods like TF-IDF, and then training the model to classify emails as spam or not spam. Logistic Regression predicts the probability of an email being spam based on its content, providing an accurate solution.


**Spam Mail Detection Overview**

0. MODEL ACCURACY :
   
    Accuracy on training data :  0.9670181736594121
    Accuracy on test data :  0.9659192825112107
   
2. Data Preparation and Exploration:

  Import the required libraries (numpy, pandas, sklearn).

  Load the dataset from a CSV file using pandas.read_csv() and explore it using functions like head(), describe(), and info() to understand the structure and content of the data.

  Clean and preprocess the data by handling missing values, converting text to lowercase, removing special characters, and splitting the dataset into features (emails) and labels (spam or not spam).

2. Feature Extraction and Model Training:

  Use TfidfVectorizer from sklearn to convert the text data into numerical features by calculating the Term Frequency-Inverse Document Frequency (TF-IDF) for each word in the email.
  
  Split the dataset into training and testing sets using train_test_split() to evaluate the model's performance.
  
  Train a machine learning model (e.g., LogisticRegression) on the training data using fit() and make predictions on the test data using predict().
  
3. Evaluation and Prediction:

    Evaluate the model's performance using metrics like accuracy_score() from sklearn.
  
    Test the model on new or unseen data to determine whether the emails are spam or not, based on the model's predictions.
