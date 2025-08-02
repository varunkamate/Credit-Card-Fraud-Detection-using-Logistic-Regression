💳 Credit Card Fraud Detection using Logistic Regression
Real-time Fraud Detection with Clean Visuals, Effective Models, and Practical Deployment

# Credit-Card-Fraud-Detection-using-Logistic-Regression
📌 Overview This project is focused on detecting fraudulent credit card transactions using Logistic Regression, a classic yet powerful binary classification model. It includes the full cycle of a machine learning workflow — from data preprocessing, exploratory data analysis (EDA), model building, to saving the model for deployment.

🚀 Goal
To accurately identify frauds in transaction data and minimize false positives while preserving genuine user experience.

📊 Exploratory Data Analysis (EDA)
🔍 We explored various features to understand:

Distribution of transaction amounts

Class imbalance (fraud vs. non-fraud)

Correlation among anonymized features

Time-wise fraud patterns

✅ Visualizations: Histograms, Correlation Heatmaps, Count Plots

🧠 Model Building
✅ Algorithm: Logistic Regression
Why?

Lightweight

Interpretable

Works well with imbalanced binary data using class weights

✅ Key Steps
Feature Scaling

Train-Test Split

Accuracy, Precision, Recall, F1-Score

ROC Curve and AUC

🧪 Evaluation Metrics
Metric	Score
Accuracy	⭐ 75.5% (Varied by random state)
Precision	⚖️ Tuned to reduce false positives
ROC-AUC	📈 Used to evaluate model's discriminatory power

💾 Model Saving & Deployment Ready
Model saved using:

python
Copy code
import pickle
with open("model.pkl", "wb") as file:
    pickle.dump(model, file)
This allows seamless integration into any backend or web app!

📦 Future Scope
✅ Integrate with real-time streaming APIs (Kafka, Spark)

📉 Try advanced algorithms (XGBoost, Isolation Forest)

🌍 Deploy as REST API using Flask or FastAPI

✨ Highlights
✅ Clean and well-documented Jupyter Notebook

🧹 Proper preprocessing and scaling

📈 Insightful EDA with plots

🔒 Model saved for production

🧑‍💻 Author
Varun Kamate

Feel free to ⭐ star the repo if you found it helpful!
Pull requests and issues are welcome.
