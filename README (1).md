
# 📊 Sentiment Analysis of Amazon Product Reviews using VADER

This project performs sentiment analysis on amazon product reviews using the **VADER (Valence Aware Dictionary and Sentiment Reasoner)** sentiment analysis tool from NLTK. The analysis includes visualizations of sentiment scores and insights derived from customer review ratings (1–5 stars).

 ## 🔍Project Description

The goal of this project is to analyze customer sentiment from review text and explore how sentiment correlates with user-provided star ratings. The dataset is uploaded in ZIP format containing a CSV file with product reviews and star scores.

Using **VADER**, we extract positive, neutral, negative, and compound sentiment scores for each review. These are then analyzed and visualized using bar plots for deeper insight into review patterns and customer satisfaction.







## ✅Features


- Load and preprocess a zipped CSV file containing reviews.
- Clean and extract relevant columns: `Score` and `Text`.
- Use **VADER SentimentIntensityAnalyzer** to score review texts.
- Visualize:
  - Distribution of reviews by star rating.
  - Average sentiment scores per rating (positive, neutral, negative, compound).
- Identify:
  - Most positive review based on sentiment score.
  - Most negative review.
  - Filter reviews based on a specific star rating.


## ✅New Feature Added By Me

 ## 🗂️  How to Use

1. Upload your ZIP file containing the CSV with `Score` and `Text` columns.
2. Run the notebook to:
   - Visualize review distributions.
   - Get sentiment scores.
   - Analyze review texts interactively.

---

##  📌 Notes

- Only the first 500 reviews are used for fast and focused analysis.
- The CSV inside the ZIP must contain at least the columns `Score` and `Text`.

 ## 📦 Tools & Libraries Used

# Package And its Purpose 

 1.pandas - Data manipulation and cleaning 
 2.matplotlib - Plotting and visualization 
 3.seaborn - Enhanced data visualizations
 4.nltk - Sentiment analysis using VADER 
# Platform I used to Run Code 
 
 # google.colab 
 File upload support in Colab 
 zipfile, io Unzipping uploaded data file and byte handling 

 ## 📈 Visualizations

- Bar plot showing the count of reviews by star rating.
- Sentiment analysis bar plots:
  - **Positive**, **Neutral**, **Negative**, and **Compound** sentiments grouped by star rating.
- Sample review outputs for most positive/negative reviews and user-selected ratings.



