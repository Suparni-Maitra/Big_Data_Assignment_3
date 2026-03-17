# Big_Data_Assignment_3
This repository contains a full-stack, end-to-end implementation of various Recommender System architectures. Using the MovieLens dataset, this project evolves from foundational Collaborative and Content-Based Filtering methods into advanced Deep Learning, Reinforcement Learning, and Explainable AI (XAI) models.

The goal of this assignment is not just to predict user ratings with high accuracy, but to dynamically adapt to long-term user preferences and provide transparent, human-readable explanations for every recommendation.

Dataset

Source: MovieLens 100K Dataset
Features: User ratings, movie metadata (release year, 19 distinct genres), and engineered features (user-genre biases, global movie popularity).

Technologies & Libraries Used

Data Processing: pandas, numpy
Traditional ML & Recommenders: scikit-learn, scikit-surprise
Deep Learning: TensorFlow / Keras
Reinforcement Learning: Custom tabular Q-Learning & MAB environments
Explainability (XAI): shap, lime

Installation and Usage
Clone the repository:

Bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Download the Dataset:
Ensure the MovieLens dataset files (u.data, u.item) are placed in the root directory.

Run the Notebooks:
The code is structured for Google Colab or local Jupyter environments. Install the required dependencies within your environment:

Bash
pip install pandas numpy scikit-learn scikit-surprise tensorflow shap lime
Execute the notebooks sequentially to trace the evolution from baseline models to XAI.

Evaluation Metrics
Models across all tasks are rigorously evaluated using:

Root Mean Squared Error (RMSE): To measure absolute rating prediction accuracy.

Precision@K & Recall@K: To measure ranking quality and the relevance of top-N recommendations.

