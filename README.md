# Sentiment-Analysis-on-Amazon-Reviews
In this Jupyter notebook we perform Sentiment Analysis for the Amazon Software dataset using Bag-of-Words.
The Amazon Softare dataset is taken from this link: https://nijianmo.github.io/amazon/index.html

We use BOW (Bag-of-Words) to perform Sentiment Analysis.

We use two sources of data:

(1) one zip file -i.e., "Software.json.gz"- contain the main dataset, and it contains the reviews of the clients;

(2) another zip file -i.e., "meta_Software.json.gz"- contains the "title" of the product (i.e., the name of the product), and it contains the brand of the product and the main category of the product.

The two datasets are merged together using the product ID which is included in both datasets.

Description of the main variables in the main dataset (i.e., "Software.json.gz"):

reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
asin - ID of the product, e.g. 0000013714
