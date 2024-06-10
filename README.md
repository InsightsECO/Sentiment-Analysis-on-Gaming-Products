<h1>Sentiment Analysis on Gaming Products</h1>

<h2>Overview</h2>

<p>Brief introduction to the project, highlighting the purpose and significance of sentiment analysis on gaming product reviews.</p>

<h3>Business Problem</h3>

<p><strong>Questions Addressed:</strong></p>
<ul>
  <li>Identify brands with higher reviews.</li>
  <li>Determine which brands' products are mostly recommended.</li>
  <li>Analyze sentiments for each gaming product.</li>
</ul>

<h3>Business Solutions</h3>

<p>Associating positive and negative words/sentiments for each gaming product using sentiment analysis.</p>
  
<h3>Assumptions</h3>

<ul>
  <li>Sample size of 5K examples is assumed to be sufficient.</li>
  <li>Information in text reviews is expected to be rich enough for sentiment analysis.</li>
</ul>

<h2>Data Collection</h2>

<p>Description of the dataset collected from Data.word.org.</p>
<p>Details about the gaming products from GameStop.</p>

<h2>Exploratory Data Analysis (EDA)</h2>

<p>Utilized Pandas, Matplotlib, Seaborn for analysis.</p>
<p>Visualized data distribution, brand frequencies, and ratings counts.</p>

<h2>Data Splitting (Train/Test)</h2>

<p>Split the data into training and test sets using Stratified Shuffle Split.</p>

<h2>Data Exploration in Training Set</h2>

<p>Explored reviews, brand frequencies, and average ratings.</p>
  
<h3>Sentiment Analysis</h3>

<p>Used Multinomial Naive Bayes, Logistic Regression, Linear SVC, Decision Tree, and Random Forest classifiers.</p>

<h3>Feature Extraction</h3>

<p>Utilized Bag of Words strategy and TfidfTransformer for feature extraction.</p>

<h3>Model Testing</h3>

<p>Tested multiple classifiers and selected Support Vector Machine (SVM) with the highest accuracy.</p>

<h3>Model Fine-Tuning</h3>

<p>Conducted Grid Search to find optimal parameters for SVM.</p>

<h2>Results</h2>

<p>Evaluated the final classifier's accuracy and provided a classification report.</p>
<p>Confusion matrix visualization for a detailed overview of the results.</p>

<h2>Future Enhancements</h2>

<p>Suggested improvements, potential additional features, or areas for further exploration.</p>
