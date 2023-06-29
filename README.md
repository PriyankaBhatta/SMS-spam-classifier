# SMS-spam-classifier

This project is an SMS/Email classifier that determines whether a given message is spam or not spam. It utilizes a dataset from Kaggle specifically designed for SMS spam classification. The classifier was developed using Python in a Jupyter Notebook environment and later integrated into a web application using Streamlit in Visual Studio Code (VSCode).

Project Overview
The project follows the following steps:

**Data Loading:** The SMS spam classifier dataset from Kaggle is loaded into the Jupyter Notebook. This dataset contains labeled SMS messages indicating whether they are spam or not spam.

**Data Preprocessing:** The loaded dataset is preprocessed to prepare it for training the classifier. This includes removing any unnecessary characters, transforming text into numerical features, and splitting the data into training and testing sets.

**Exploratory Data Analysis (EDA):** Exploring the dataset to gain insights into the distribution of spam and non-spam messages, identifying any patterns, and understanding the characteristics of the data.

**Model Building:** Developing a machine learning model to classify SMS/email messages as spam or not spam. Various classification algorithms can be used, such as Naive Bayes, Logistic Regression, or Support Vector Machines (SVM). The model is trained using the preprocessed data.

**Prediction:** The trained model is used to predict the classification of new, unseen messages. This step involves transforming the input text into numerical features and applying the trained model to make predictions.

**Model Persistence:** The trained model is serialized using the pickle library to store it as a binary file. This allows for easy retrieval and usage in other environments.

**Web Application Development:** The serialized model is imported into a web application framework, such as Streamlit. The framework is used to build a user-friendly interface where users can input text messages/emails to be classified as spam or not spam.

The link to kaggle dataset: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

The website looks like this:
![1](https://github.com/PriyankaBhatta/SMS-spam-classifier/assets/109200742/e622ea52-0fae-4bed-aba7-2fcefc333653)
![2](https://github.com/PriyankaBhatta/SMS-spam-classifier/assets/109200742/4056a964-f829-413e-8741-a097c149482b)

