# Parallelized SON Algorithm for Frequent Itemset Mining
This project implements a parallelized version of the SON algorithm using Apache Spark for frequent itemset mining. The Apriori algorithm is used for local itemset mining within partitions, and the implementation is tested on a dataset of Amazon book reviews to identify books frequently *liked* together by users.

**Dataset:** Amazon Book Reviews (3M reviews, 221,998 books).\
**Frequent Itemsets Mined:** 16,854 (min support = 0.01%).\
**Execution Time:** ~4 minutes.\
**Scalability:** Efficient performance observed with varying dataset sizes, support thresholds, and itemset sizes.

**Google Colab version of the notebook:**
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julwdo/Algorithms-project/blob/main/Algorithms_Project_JW.ipynb)
