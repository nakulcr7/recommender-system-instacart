# Recommender Systems For Instacart: A Collaborative Filtering Approach

## Collaborators

- Nakul Camasamudram
- Guiheng Zhou
- Rahul Verma
- Rosy Parmar


Exploratory data analysis is performed in `src/eda.ipynb`.

We have implemented three collaborative filtering methods in independent Jupyter Notebooks under `src/`
1. `tfidf.ipynb`: Neighborhood based method that uses cosine similarity on a tf-idf weighted matrix to recommend products from similar users.
2. `svd.ipynb`: Matrix factorization using SVD. Computes the largest K singular values/vectors for a sparse matrix. Based upon the largest K singular values, we find top K recommended items for users.
3. `imf.ipynb`: Matrix factorization using Alternating Least Squares by representing the utility matrix as a confidence matrix. Based on the paper [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf).

More details are in `documents/final/report.pdf`

Video presentation [here](https://www.youtube.com/watch?v=U0MezTRQsuw&feature=youtu.be).

## Usage

- Install dependencies: `pip install -r requirements.txt`.
- Download all *.csv's from [here](https://www.instacart.com/datasets/grocery-shopping-2017) into the data/ directory.
- Run any of the Jupyter Notebooks under `src/`
- You can view the evaluation results in data/eval. [It is currently empty. Will be populated if the notebooks are run again.]
