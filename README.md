# Youtube_Video_Sentiment_Analysis

### YouTube Video Sentiment Analysis

This project focuses on analyzing the sentiment of YouTube video comments using the YouTube Data API and the VADER sentiment analysis tool. Here’s a summary of what the code does:

#### Summary

1. **Fetching Video Details:**
   - Retrieves basic information about a YouTube video such as its title, number of likes, view count, and comment count using the YouTube Data API.

2. **Fetching Comments:**
   - Collects comments from a YouTube video using the YouTube Data API. The comments are sorted by relevance and a maximum of 3000 comments can be fetched.

3. **Sentiment Analysis:**
   - Utilizes the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from NLTK to assess the sentiment (positive, negative, neutral) of each comment.

4. **Visualization:**
   - Generates word clouds to visually represent the most frequent words used in all comments and in selected comments (randomly chosen subset for analysis).

5. **Overall Video Sentiment:**
   - Determines the overall sentiment of the video based on the sentiment scores of the comments. It calculates the ratio of positive to negative comments to assign a sentiment category (positive, negative, neutral).

6. **Top Positive and Negative Comments:**
   - Identifies and prints the top positive and top negative comments based on their sentiment scores.

7. **Visualization of Sentiment Distribution:**
   - Presents a bar chart to illustrate the distribution of sentiment categories (positive, negative, neutral) among the selected comments.

8. **Percentage Calculation:**
   - Computes the percentage of positive, negative, and neutral comments out of the total selected comments.

#### Benefits of the Project

- **Insight Generation:** Provides insights into public sentiment towards a YouTube video, which can be valuable for content creators, marketers, and analysts.
  
- **Automated Analysis:** Automates the process of collecting and analyzing comments, saving time and effort compared to manual methods.

- **Visual Representation:** Visualizes sentiment and word usage patterns through word clouds and bar charts, making it easier to interpret results.

#### Future Work

- **Enhanced Sentiment Analysis:** Incorporate machine learning models for sentiment analysis to potentially improve accuracy and handle more complex language nuances.
  
- **User Interface:** Develop a user-friendly interface to input video URLs and display analysis results graphically.
  
- **Real-Time Analysis:** Implement real-time monitoring of comments to capture evolving sentiment trends.

---

This project leverages YouTube's API and sentiment analysis techniques to offer a comprehensive view of how viewers perceive video content based on their comments. It can be expanded further with more advanced sentiment analysis models and interactive features for broader applicability.
