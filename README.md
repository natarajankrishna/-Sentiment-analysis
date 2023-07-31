# -Sentiment-analysis
**Sentiment Analysis from Google Play Store Reviews**
**GOAL**: 
This project aims to develop a sentiment analysis model using a dataset of over 12,000 reviews from real users of various applications on the Google Play Store. The primary objective is to accurately classify the reviews as positive or negative based on the sentiments expressed by the users.

**Dataset** :
The provided dataset comprises more than 12,000 genuine user reviews for various applications on the Google Play Store. Each review is accompanied by a rating, which allows for classification into positive or negative sentiments.

**Preprocessing Steps** :
Before training the sentiment analysis model, the dataset underwent various preprocessing steps to clean and prepare the text for analysis. The following preprocessing steps were applied:
- Stopword Removal: Commonly used words with little sentiment information were removed from the text.
- Hyperlink Removal: URLs and hyperlinks present in the reviews were removed.
- Number and Digit Removal: Numeric characters and digits were removed from the text.
- Punctuation and Special Character Removal: Punctuation marks and special characters were removed.
- Emoji Handling: Emojis were removed from the text to focus on textual sentiment analysis.
- Tokenization: The text was split into individual words or tokens for further processing.
- Vectorization: The tokenized text was converted into numerical vectors for model training.

**Classification Model** :
A Multinomial Naive Bayes (MultinomialNB) classifier was used for sentiment classification. The classifier is well-suited for text classification tasks, especially when dealing with discrete features like word counts.

**Conclusion** : 
The sentiment analysis model demonstrated promising results, achieving an overall accuracy of 80%. However, as with any machine learning project, there is always room for improvement. Further fine-tuning hyperparameters, exploring other classifiers, or using deep learning techniques could enhance the model's performance.

This project showcases the power of sentiment analysis in understanding customer sentiments from reviews. It can be utilized to gain valuable insights into user feedback on applications on the Google Play Store.
