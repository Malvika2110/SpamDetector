LIVE WEBSITE URL GENERATED USING RENDER
https://spamdetector-1.onrender.com

Project Report: SMS+EMAIL Spam Detection System

Introduction
SMS and EMAIL spam poses a significant challenge in ensuring secure and efficient
communication. These spam messages often contain malicious content, such as phishing links
or unsolicited advertisements, which compromise user productivity and security. To address this
issue, our project focuses on developing a spam and email detection system leveraging
machine learning to classify SMS and Email messages as either spam or ham (legitimate). This
application is implemented using Flask and trained on a publicly available dataset.

Objective
The primary objective of this project is to create a user-friendly web application capable of:
1. Accurately classifying SMS and EMAIL messages as spam or ham.
2. Providing an interactive interface for users to input messages and receive real-time
predictions.
3. Ensuring the model is adaptable and efficient for real-world use cases.

Methodology
1. Data Collection:
The dataset for this project was sourced from Kaggle. It contains labeled
SMS/Email messages categorized as "spam" or "ham."

3. Data Preprocessing:
- Remove unwanted characters, punctuation, and stopwords to clean the dataset.
- Converted text data into numerical format using Term Frequency-Inverse
Document Frequency (TF-IDF).

4. Model Training:
- Trained the data using logistic regression machine learning model
- Evaluated models based on accuracy and precision
- Used SVM to predict the models F Scores and accuracy score

5. Web Framework Implementation:
- Built a Flask-based web application to provide an interactive interface for the
user.
- Integrated the trained machine learning model for real-time predictions.

Implementation
1. Development Tools and Frameworks:
- Programming Language: Python
- Framework: Flask
- Libraries: Pandas, Scikit-learn, NLTK, TF-IDFVectorizer

2. Web Application Flow:
- Input: Users enter a message through the web interface.
- Processing: The message is preprocessed and fed into the trained model.
- Output: The model predicts whether the message is spam or ham, displaying the
result instantly.

3. Deployment:
- The application is hosted locally using Flask, allowing users to interact with the
model on their browsers.

Results
1. Model Performance:
- Achieved an accuracy of approximately 97.7% on the testing dataset.

2. Application Feedback:
- Successfully classified a variety of user inputs around 5500 during testing,
demonstrating real-world viability.

3. Delivered results with minimal latency, ensuring a smooth user experience.

Conclusion
The SMS and Email Spam Detection system is an efficient and accurate solution for identifying
spam messages. By leveraging machine learning techniques and a user-friendly Flask interface,
the project demonstrates the potential to enhance communication security significantly. Future
enhancements may include deploying the application on cloud platforms, incorporating
additional datasets, and extending support for other languages.

Future Scope
1. Deploy the application on a cloud platform like AWS, Azure, or Heroku for broader
accessibility.
2. Incorporate real-time SMS and email data to continuously train and improve the model's
accuracy.
3. Expand support to detect spam in other communication mediums, such as emails or
social media messages.
4. Implement advanced Natural Language Processing (NLP) models, like transformers, for
enhanced performance.
