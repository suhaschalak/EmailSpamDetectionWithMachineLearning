## TASK 2 - Gmail Spam Detection Using Machine Learning

This project focuses on categorizing incoming emails as spam or not spam (ham) using machine learning. By applying natural language processing (NLP) techniques, the model analyzes the content of messages and calculates the probabilities of them being classified as spam. The goal is to enhance email filtering systems and help users avoid unwanted or potentially dangerous messages.

### Features:
- **Email:** The content of the email, which includes both the subject and body text.
- **Label:** Classifies the email as either spam or not spam.

### Project Structure:
1. **Data Preprocessing:** This includes tokenizing, cleaning, and vectorizing email data by removing punctuation, converting text to lowercase, and eliminating stopwords.
2. **Feature Extraction:** Techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) are employed to convert email text into numerical features for analysis.
3. **Model Training:** Various machine learning models, including Gaussian Naive Bayes, Multinomial Naive Bayes, Bernoulli Naive Bayes, and a Voting Classifier, are trained to classify the emails.
4. **Model Evaluation:** The performance of the models is assessed using metrics like accuracy and precision.
5. **Web Interface:** A simple web application is built using Streamlit, enabling users to input email content and receive predictions on whether the email is spam or not.

### Best Performing Model:
The best performing model is **Multinomial Naive Bayes**, which effectively classifies emails with high accuracy.
