# Sentiment-Analysis-of-Customer-Reviews-using-NLP-ML

🌍 Global Customer Support Agent - NLP Sentiment Analysis
This project aims to build a sentiment analysis model using Natural Language Processing (NLP) to automatically classify customer reviews as Positive 😊 or Negative 😞. It is designed to simulate the role of a Global Customer Support Agent that can process large volumes of customer feedback and assist in real-time understanding of user sentiment.

📁 Dataset Used
Amazon Product Reviews (Reviews.csv)

Contains over 500,000 product reviews.

Only 2 columns used: Text (review) and Score (rating from 1 to 5).

Neutral reviews (score = 3) are removed.

Sentiment labels:

Positive: Score > 3 → 1

Negative: Score < 3 → 0

📊 Visualizations
The following visualizations were created using Seaborn and Matplotlib:

Sentiment Distribution CountPlot

Word Count Histogram

Text Length Boxplot

Word Count Violinplot by Sentiment

🧠 Models Trained
Four machine learning models were trained and evaluated using TF-IDF vectorization and 80/20 train-test split:

Logistic Regression

Naive Bayes (MultinomialNB)

Random Forest Classifier

Support Vector Machine (LinearSVC)

The model with the highest accuracy was used for real-time predictions.

📝 Workflow
Data Cleaning & Preprocessing

Text Vectorization using TF-IDF

Visualization for EDA

Model Training (4 ML models)

Evaluation (Confusion Matrix, Classification Report, Accuracy)

User Input Prediction System

🧪 Final Feature: User Input Prediction
The final section of the notebook includes a real-time prediction loop, allowing the user to enter any review, which is then classified using the best model.

bash
Copy
Edit
Enter a review (or type 'exit' to stop): I loved this product, it's amazing!
Predicted Sentiment: Positive 😊
🛠 Technologies Used
Python 🐍

Pandas

Matplotlib / Seaborn

Scikit-learn

NLP (TF-IDF)

📦 How to Run
bash
Copy
Edit
1. Clone the repository
2. Install dependencies (scikit-learn, pandas, seaborn, etc.)
3. Run the `Global_Customer_Support_Agent.ipynb` notebook
4. Test your own reviews in the prediction cell
🚀 Future Work
Deploy as a web app (Flask/Streamlit)

Add multilingual support

Add emotion analysis (e.g., happy, angry, sad)

👤 Author
Shalini Kumari
B.Tech in Data Science | Open-Source Contributor | AI Enthusiast
Contact: shalinis19137@gmail.com
