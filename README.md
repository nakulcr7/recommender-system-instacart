# Recommender Systems For Instacart: A Collaborative Filtering Approach
## CS 6220 Project: Team 07

Exploratory data analysis was performed initially in `src/eda.ipynb`.

We have implemented three collaborative filtering methods in independent Jupyter Notebooks under `src/`
1. `tfidf.ipynb`: Neighborhood based method that uses cosine similarity on a tf-idf weighted matrix to recommend products from similar users.
2. `method2.ipynb`:
3. `imf.ipynb`: Matrix factorization using Alternating Least Squares by representing the utility matrix as a confidence matrix for better results. Based on the paper [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf).

Execution steps:
----------------
1. Install dependencies: `pip install -r requirements.txt`.
2. Download all *.csv's from [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data) into the `data/` directory.
3. Run any of the Jupyter Notebooks under `src/`