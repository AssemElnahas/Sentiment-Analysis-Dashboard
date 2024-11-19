 Sentiment Analysis Dashboard

This is a simple sentiment analysis dashboard built using Python and Streamlit. The app uses **TextBlob** for analyzing the sentiment of the text input. The sentiment analysis provides polarity and subjectivity scores, as well as a classification of whether the sentiment is positive, negative, or neutral.

 Features:
- Real-time sentiment analysis of any text input.
- Displays polarity (from -1 to 1) and subjectivity (from 0 to 1).
- Positive, negative, or neutral sentiment classification.

 Requirements:
Before running the app, make sure you have the following libraries installed:
- Streamlit: For the dashboard interface.
- TextBlob: For sentiment analysis.

You can install the required libraries using `pip`:

bash
pip install streamlit textblob


 How to Run the App:

1. Clone or download this repository to your local machine.
2. Navigate to the directory where the file is saved using the terminal/command prompt.
3. Run the Streamlit app with the following command:

bash
streamlit run sentiment_dashboard.py


4. The app will open in your default browser. You can then enter any text in the input box, and the sentiment analysis results will be displayed in real-time.

 Example Inputs:
- Positive Input:  
    I had a wonderful experience at the new restaurant. The food was delicious and the staff was very friendly and attentive.
- Negative Input:  
    The product quality was terrible, and it stopped working after a few days. Customer service was unhelpful and rude.
- Neutral Input:  
    "The weather is expected to be cloudy with a chance of rain tomorrow."

Output:
- Polarity: A value ranging from -1 (negative sentiment) to 1 (positive sentiment).
- Subjectivity: A value ranging from 0 (objective) to 1 (subjective).
- Interpretation: The app will display whether the sentiment is positive, negative, or neutral.

 License:
This project is open-source and free to use.



