# Spam-Email-Classification-Project
<h1>Description</h1>
<p>This project is about creating a machine learning-based application to determine whether a given email is spam or not. This system processes text emails, classifies it as either "Spam" or "Ham," which refers to the absence of spam, and therefore helps to increase email security through filtering of unwanted messages. This model is efficient because it uses natural language processing techniques in its analysis to classify content.</p>
<h1>Technologies used</h1>
<h2>python libraries</h2>
<p>Streamlit: For building the web application interface</p>
<p>Pandas: For data manipulation and preprocessing.</p>
<p>Numpy: For numerical computations.</p>
<p>Scikit-learn: For building and evaluating the machine learning model.</p>
<p>Pickle: For saving and loading the trained model and vectorizer.</p>
<h2>Machine Learning Algorithm</h2>
<p>Multinomial Naive Bayes: Used for text classification due to its effectiveness in dealing with categorical data like text.</p>
<h2>Natural Language Processing:</h2>
<p>CountVectorizer: Converts text data into a matrix of token counts, used as input to the model.</p>
<h1>Environment Setup:</h1>
<h3>Install Python and the required libraries:</h3>
<p>pip install streamlit pandas numpy scikit-learn</p>
<h3>Prepare the Data:</h3>
<p>Load and preprocess the spam.csv dataset. Ensure that unnecessary columns are dropped and the data is encoded properly.</p>
<h3>Train the Model:</h3>
<p>Train a MultinomialNB model using the email text data and save the trained model (spam.pkl) and vectorizer (vec.pkl) using pickle.</p>
<h3>Run the Streamlit App:</h3>
<p>Open a terminal and navigate to the project directory containing the spamDetector.py file.</p>
<h3>>Execute the command:</h3>
<p>streamlit run spamDetector.py
This will launch the web application in your default browser.</p>
<h3>>Classify Emails:</h3>
<p>Enter email content in the text box provided on the application and click "Classify." The app will display whether the email is "Spam" or "Not Spam."</p>
