📢 Live Tweets Sentiment Analysis Model

📌 Overview

This project fetches real-time tweets containing media (images/videos) using Tweepy v2 and analyzes their sentiment (Positive, Negative, Neutral) using TextBlob. It includes visualizations like pie charts, bar graphs, and word clouds to understand sentiment trends.

🚀 Features

✅ Fetches live tweets from Twitter (X) API v2

✅ Filters tweets with media (images/videos) only

✅ Performs Sentiment Analysis using TextBlob

✅ Visualizes results with Pie Charts, Bar Graphs & Word Clouds

✅ Secures API keys using a .env file

🛠️ Technologies Used

Python – (for model development)

Tweepy v4 – (for fetching live tweets)

TextBlob – (for Sentiment Analysis)

Matplotlib & Seaborn – (for visualizations)

WordCloud – (for word cloud generation)

NLTK – (for text preprocessing)

Dotenv – (for securely loading API keys)

🔑 Twitter API Access Requirements

To run this project, you must have access to: 

✔ Twitter API v2

✔ Read-Only Access for Media Tweets

✔ Bearer Token (Required for v2)

📊 How It Works

1️⃣ Authenticates Twitter API v2 using a secure .env file

2️⃣ Fetches live tweets containing images/videos using Tweepy

3️⃣ Cleans tweets (removes URLs, mentions, hashtags)

4️⃣ Performs Sentiment Analysis (Positive, Negative, Neutral)

5️⃣ Visualizes results with Pie Chart, Bar Graph, and WordCloud

⚙️ Installation & Usage

1️⃣ Install Required Dependencies

pip install --upgrade tweepy pandas textblob matplotlib seaborn wordcloud python-dotenv

2️⃣ Save Twitter API Keys in .env File

Create a file named .env and add your API keys:

API_KEY=your_api_key

API_SECRET=your_api_secret

ACCESS_TOKEN=your_access_token

ACCESS_SECRET=your_access_secret

BEARER_TOKEN=your_bearer_token

3️⃣ Run the Model

python live_tweet_sentiment.py

📈 Visualizations Included

📊 Pie Chart: Sentiment Distribution

📊 Bar Graph: Count of Positive, Negative, Neutral tweets

☁️ WordCloud: Most common words in Positive & Negative tweets

📜 License

This project is open-source and free to use for educational purposes.
