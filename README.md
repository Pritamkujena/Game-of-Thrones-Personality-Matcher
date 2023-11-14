# Game-of-Thrones-Personality-Matcher
The "Game of Thrones Personality Matcher" is a project that leverages sentiment analysis and dimensionality reduction techniques to analyze and compare the personalities of characters from the popular television series "Game of Thrones." The project includes two main components:

Sentiment Analysis:

The sentiment analysis component analyzes the sentiment of the dialogue spoken by each character in "Game of Thrones."
It uses the VADER sentiment analysis tool to calculate sentiment scores for each character's dialogue.
The sentiment scores provide an indication of the emotional tone of the characters, allowing for the identification of characters with positive or negative sentiments.
Personality Matching with t-SNE:

The project utilizes t-Distributed Stochastic Neighbor Embedding (t-SNE), a dimensionality reduction technique, to represent the personalities of characters in a lower-dimensional space.
Each character is assigned coordinates in this reduced feature space based on the bag-of-words representation of their dialogue.
A Streamlit web application is created to allow users to interactively explore and find character matches based on their personalities.
Users can select a character from the available options, and the application calculates the character with the closest personality match using Euclidean distances in the reduced feature space.
The application provides visualizations, including images of the selected character and their closest match, enhancing the user experience.
