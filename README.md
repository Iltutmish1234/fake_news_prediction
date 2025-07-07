# fake_news_prediction
📰 <b>Fake News Prediction using Machine Learning :</b>
<br>This project focuses on detecting fake news using Natural Language Processing (NLP) and machine learning algorithms. It uses Logistic Regression and Support Vector Machine (SVM) models to classify news articles as fake or real, based on their textual content.

📌<b> Project Highlights :</b>
<br>Implemented text preprocessing techniques like tokenization, stopword removal, and stemming.<br>
Visualized class distribution using Countplot.<br>
Evaluated performance using confusion matrix, accuracy, and ROC curves.<br>

📌<b>Built classification Models Using :</b> <br>
 Logistic Regression<br>
 Support Vector Machine (SVM) <br>
 
📁<b> Dataset :</b>
<br>The dataset used is a collection of real and fake news articles, with text and labels.

🔧 <b>Tech Stack :</b>
<br>Python<br>
Pandas, NumPy<br>
scikit-learn – for ML models<br>
NLTK – for text preprocessing<br>
Matplotlib, Seaborn – for visualizations

🧹<b> Text Preprocessing :</b>
<br>Lowercasing<br>
Tokenization<br>
Stopword removal (using NLTK)<br>
Stemming (Porter Stemmer)

🤖 <b>Model Training :</b>
<br>Logistic Regression :<br>
Trained on TF-IDF features<br>
Evaluated using accuracy, confusion matrix, and ROC-AUC. <br>

Support Vector Machine (SVM) :<br>
 Applied linear kernel<br>
 Performed hyperparameter tuning (if any)

📌 <b>Conclusion :</b>
<br>Both models performed well on the dataset, with SVM slightly outperforming in terms of precision.<br>
Logistic Regression was faster to train and interpret.<br>
The countplot revealed a balanced/unbalanced dataset.
