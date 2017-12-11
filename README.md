# Recommender Systems For Instacart: A Collaborative Filtering Approach
## CS 6220 Project: Team 07

We have implemented three collaborative filtering methods in independent Jupyter Notebooks under `src/`
1. tfidf: <- Change name to actual and a one line description here
2. method2:
3. imf: Matrix factorization using Alternating Least Squares by representing the utility matrix as a confidence matrix for better results. Based on the paper [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf).

Before implementing any of the methods, we performed exploratory data analysis in `src/eda.ipynb`.

Pre-run steps:
--------------
1. Install dependencies: `pip install -r requirements.txt`.
2. Download all *.csv's from [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data) into the `data/` directory.
3. Run any of the Jupyter Notebooks under `src/`