
# Comprehensive Analysis of ChatGPT User Reviews

This repository contains an in-depth analysis of user reviews and ratings for the ChatGPT Android App. The analysis is performed using a Jupyter Notebook, which includes sentiment analysis, temporal trends, score distribution, thumbs up analysis, and more.

## Dataset Description

The dataset consists of daily-updated user reviews and ratings for the ChatGPT Android App, including the following key attributes:

- **userName**: The display name of the user who posted the review.
- **content**: The text content of the review, which includes user opinions and feedback.
- **score**: The rating given by the user, typically ranging from 1 to 5.
- **thumbsUpCount**: The number of thumbs up (likes) the review received.
- **at**: The timestamp of when the review was posted.

This dataset can be found in **Kaggle**: [ChatGPT User Reviews](https://www.kaggle.com/datasets/bhavikjikadara/chatgpt-user-feedback)

## Analysis Overview

### 1. Sentiment Analysis
The VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool is used to determine the sentiment of the reviews. VADER is specifically attuned to sentiments expressed in social media.

### 2. Temporal Trends
The temporal distribution of reviews is analyzed to understand how user feedback changes over time.

### 3. Score Distribution
The distribution of scores is examined to understand overall user satisfaction with the ChatGPT app.

### 4. Thumbs Up Analysis
The thumbs up counts are analyzed to identify the most helpful reviews based on the number of likes they received.

### 5. Text Length Analysis
The length of the review texts is analyzed  to see if there is any correlation between the length of the review and the score given.

### 6. Additional Insights
The common words used in positive and negative reviews are analyzed to gain further insights into user sentiments.


### Insights
1. **Sentiment Analysis**:
   - The majority of the reviews are positive, indicating that most users have a favorable opinion of the ChatGPT app.
   - The sentiment analysis shows a clear distinction between positive and negative reviews based on the compound score.

2. **Temporal Trends**:
   - There is a noticeable trend in the number of reviews over time. Peaks in the number of reviews could correlate with app updates or major events related to ChatGPT.
   - Analyzing the trends can help identify periods of increased user engagement and feedback.

3. **Score Distribution**:
   - The score distribution reveals that most users rate the app highly, with a significant number of 5-star reviews.
   - There are also some low scores, which can provide insights into areas where the app may need improvement.

4. **Thumbs Up Analysis**:
   - Reviews with higher thumbs up counts are considered more helpful by other users.
   - Analyzing these reviews can provide valuable insights into common positive and negative feedback.

5. **Text Length Analysis**:
   - The length of the review text varies significantly, with some users providing detailed feedback while others leave short comments.
   - There is a relationship between text length and score, with more detailed reviews often correlating with higher or lower scores.

6. **Common Words in Reviews**:
   - The word clouds for positive and negative reviews highlight the most frequently mentioned words, providing insights into common themes and issues raised by users.

### Conclusion
The analysis of the ChatGPT user reviews dataset provides valuable insights into user sentiments, trends, and feedback. Most users have a positive experience with the app, as reflected in the high number of positive reviews and high scores. However, there are areas for improvement, as indicated by the negative reviews and lower scores.

By continuously monitoring user feedback and analyzing trends, the developers of the ChatGPT app can identify areas for improvement and enhance the overall user experience. The insights gained from this analysis can guide future updates and feature enhancements to better meet user needs and expectations.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/debjit-mandal/chatgpt-reviews-analysis.git
    ```
2. Navigate to the cloned repository:
    ```bash
    cd chatgpt-reviews-analysis
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook chatgpt_reviews_analysis.ipynb
    ```
2. Run the cells in the notebook to perform the analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The dataset was collected from the Google Play Store reviews section for the ChatGPT Android App.
- The sentiment analysis was performed using the VADER sentiment analysis tool.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

-----------------------------------------------------------------------------