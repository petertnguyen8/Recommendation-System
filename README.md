Recommendation Engine with Matrix Factorization

📖 About the Project

This project is the capstone for the Udacity Data Science Nanodegree. The primary goal is to build a recommendation engine from scratch using real-world data from the IBM Watson Studio platform. The dataset contains user interactions with articles, and the objective is to recommend new articles that users might be interested in.

This project demonstrates a range of data science skills, including:

    Exploratory Data Analysis (EDA)

    Data Cleaning and Preprocessing

    Rank-Based Recommendations

    User-User Collaborative Filtering

    Matrix Factorization (SVD)

    Evaluation and Validation of Recommendation Systems

🛠️ Built With

    Python

    Jupyter Notebook

    NumPy

    pandas

    Matplotlib

    Scikit-learn

🚀 Getting Started

To get a local copy up and running, follow these simple steps.

Prerequisites

You'll need to have Python and pip installed on your machine. You can download them from python.org.

Installation

    Clone the repo:
    Bash

git clone https://github.com/petertnguyen8/Recommendation-System.git

Navigate to the project directory:
Bash

cd Recommendation-System

Install the required packages:
Bash

    pip install -r requirements.txt

    (Note: You may need to create a requirements.txt file)

USAGE

    Open the Jupyter Notebook:
    Bash

    jupyter notebook

    In the Jupyter Notebook interface, navigate to and open the .ipynb file to see the step-by-step implementation of the recommendation engine.

📈 Methodology

The project is divided into several key parts:

    Exploratory Data Analysis: The first step is to load and explore the dataset to understand the distribution of user-article interactions.

    Rank-Based Recommendations: As a baseline, the most popular articles are recommended to all users. This is a simple but effective method for new users (the "cold start" problem).

    User-User Collaborative Filtering: This method recommends articles to a user based on the articles that similar users have liked.

    Matrix Factorization with SVD: For a more advanced approach, Singular Value Decomposition (SVD) is used to predict user-article interactions. This technique helps to uncover latent features that can explain the observed ratings.

    Evaluation: The performance of the recommendation engine is evaluated by splitting the data into training and testing sets and measuring how well the model can predict unseen user-article interactions.



🙏 Acknowledgments

    Udacity for the Data Science Nanodegree program.

    IBM Watson Studio for providing the dataset.
