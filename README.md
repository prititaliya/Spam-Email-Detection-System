# Email-Detection-System
This project implements a Spam Email Classifier using Multinomial Naive Bayes and a machine learning pipeline. The classifier determines whether an email is spam or not based on its content.


# Features:
	1.	Data Visualization:
	•	Visualizes the distribution of spam vs. non-spam emails using pie charts.
	•	Generates a word cloud to explore frequently used words in the dataset.
	2.	Text Vectorization:
	•	Converts email text into numerical features for machine learning.
	3.	Model Training:
	•	Utilizes a Multinomial Naive Bayes model to classify emails as spam or not.
	4.	Pipeline:
	•	Combines vectorization and model training into a single pipeline for simplicity.
	5.	Custom Predictions:
	•	Supports spam classification for email content provided in text files.

# Requirements: 
	•	Python 3.7 or higher
	•	Libraries: pandas, numpy, matplotlib, seaborn, wordcloud, scikit-learn

# Usage:
	1.	Prepare the dataset (emails.csv) containing at least two columns:
	•	text: The email content.
	•	spam: Label indicating whether the email is spam (1) or not (0).
	2.	Run the script to visualize the data, train the model, and classify new emails.
	3.	Optionally, provide custom email text files to predict whether they are spam or not.


# Example Workflow:
	•	Load and preprocess the dataset.
	•	Visualize the distribution of spam vs. non-spam emails.
	•	Train the Naive Bayes model using a machine learning pipeline.
	•	Predict spam status for new email content.

### Credits:

    The project is built using publicly available email datasets and open-source Python libraries. Special thanks to the creators of these tools for enabling efficient machine learning development.