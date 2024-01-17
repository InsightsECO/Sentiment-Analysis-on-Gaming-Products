# Sentiment-Analysis-on-Gaming-Products


<p1>Overview<p1>

Brief introduction to the project, highlighting the purpose and significance of sentiment analysis on gaming product reviews.

Business Problem
Questions Addressed:
Identify brands with higher reviews.
Determine which brands' products are mostly recommended.
Analyze sentiments for each gaming product.
Business Solutions
Associating positive and negative words/sentiments for each gaming product using sentiment analysis.
Potential Suggestions for Product Reviews
Provide insights and recommendations based on the sentiment analysis.
Assumptions
Sample size of 5K examples is assumed to be sufficient.
Information in text reviews is expected to be rich enough for sentiment analysis.
Data Collection
Description of the dataset collected from Data.word.org.
Details about the gaming products from GameStop.
Exploratory Data Analysis (EDA)
Utilized Pandas, Matplotlib, Seaborn for analysis.
Visualized data distribution, brand frequencies, and ratings counts.
Data Splitting (Train/Test)
Split the data into training and test sets using Stratified Shuffle Split.
Data Exploration in Training Set
Explored reviews, brand frequencies, and average ratings.
Sentiment Analysis
Used Multinomial Naive Bayes, Logistic Regression, Linear SVC, Decision Tree, and Random Forest classifiers.
Feature Extraction
Utilized Bag of Words strategy and TfidfTransformer for feature extraction.
Model Testing
Tested multiple classifiers and selected Support Vector Machine (SVM) with the highest accuracy.
Model Fine-Tuning
Conducted Grid Search to find optimal parameters for SVM.
Results
Evaluated the final classifier's accuracy and provided a classification report.
Confusion matrix visualization for a detailed overview of the results.
Conclusion
Summarized findings, insights, and the overall success of the sentiment analysis project.

Future Enhancements
Suggested improvements, potential additional features, or areas for further exploration
