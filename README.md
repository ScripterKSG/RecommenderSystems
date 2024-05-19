This repository contains two different architechtures for bipartite graph recommender systems, Matrix Factorization and LightGCN. To use these notebooks, the dataset much be in the format of pandas dataframe with columns: user_id, book_id, and 
rating.

The dataset used can be found here:
[Goodreads Datasets](https://mengtingwan.github.io/data/goodreads.html)

Evaluated on Bayesian Personalized Ranking (BPR) Loss, Normalized Discounted Cumulative Gain (NDCG), and Mean Average Precision (MAP), we observed that LightGCN performed significantly better and scaled well in comparison to Matrix Factorization. The models were trained with a focus on positive recommendations only.

For an overview of the results, please see the pdf report.
