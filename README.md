🔮 Amazon Review Rating Prediction using IBM Watson AutoAI

This project uses IBM Watson AutoAI to automatically train and deploy a machine learning model that predicts the review rating (1 to 5 stars) of an Amazon product review based on the review text and recommendation flag.

It demonstrates how low-code/no-code tools like IBM AutoAI can be used alongside Python to build, deploy, and consume machine learning models via REST APIs.

📌 Problem Statement

Can we predict the star rating of an Amazon product review based on the text of the review and whether the user recommends it?

Use Case: Automate sentiment-to-rating conversion for e-commerce platforms to reduce manual effort in review moderation and summary.

🔹 Dataset

Source: Amazon product review dataset (subset of 100 reviews used for training)

Target: reviews.rating

Features used:

brand

name

reviews.doRecommend

reviews.text

⚙️ IBM Watson AutoAI Process

Dataset uploaded to Watson Studio Project

AutoAI automatically:

Preprocessed the data

Selected features

Tested multiple algorithms (e.g., Logistic Regression, XGBoost, etc.)

Optimized pipelines and ranked them

Best pipeline selected based on accuracy

Model deployed as an online REST API in IBM Cloud

💡 Technology Used

IBM Watson Studio (AutoAI)

IBM Cloud Machine Learning

Google Colab (for Python integration)

Python Libraries: requests, ibm-cloud-sdk-core

🚪 Model Deployment

Model deployed as a REST API on IBM Cloud

Can be tested using IBM Test tab or Python script in Google Colab

Example Prediction:
Input:

"Battery life is amazing and it's super fast"

Output:

Predicted Rating: 5.0

📁 Repository Contents

amazon_review_prediction.ipynb: Colab notebook to test the model

requirements.txt: Required Python packages

README.md: Project documentation

🚀 Future Improvements

Train on larger dataset for better generalization

Add more NLP features (e.g., sentiment score, word embeddings)

Build a frontend UI using Streamlit or Flask

👤 Author

LinkedIn- Pranjal Nikum ,
  Github- pranjalnikum31
