# Humor in Headlines: Sociolinguistic Variation 😂

## 📌 Project Overview
**Humor in Headlines** is a data science research project that aims to decode the patterns of online humor. By analyzing thousands of posts from various Reddit communities (Subreddits), the project explores how language, community norms, and context influence what makes a headline funny.

## 🎯 Objectives
* **Humor Detection:** Build machine learning models to classify text as "Humorous" or "Non-Humorous".
* **Sociolinguistic Analysis:** Investigate how different communities (e.g., r/jokes vs. r/ProgrammerHumor) utilize distinct linguistic structures and vocabulary.

## 🔄 Data Pipeline
1.  **Data Collection:** Scraped **20,000+ posts** from 19 subreddits using the **Reddit API (PRAW)** and augmented the dataset with the "Short Jokes" dataset from Hugging Face.
2.  **Preprocessing:** Cleaned text, handled emojis, and removed duplicates.
3.  **EDA:** Analyzed post lengths, emoji usage frequencies, and engagement metrics (upvotes/comments).

## 🧠 Models & Results
The project compared traditional Machine Learning against Deep Learning:
* **Logistic Regression (Baseline):** Achieved **63.5% Accuracy**. It proved effective in identifying simple linguistic cues like brevity and informal words.
* **Recurrent Neural Network (RNN):** Achieved **62.7% Accuracy**. While powerful, it struggled with the short, context-heavy nature of the headlines compared to the simpler model.
