Python  | Numpy | Pandas | Statsmodels | Sci-Kit Learn
--------|-----|-----|---------|------
[![PyPI](https://img.shields.io/badge/python-3.5-blue.svg)]() | [![PyPI version](https://badge.fury.io/py/numpy.svg)](https://badge.fury.io/py/numpy) | [![PyPI version](https://badge.fury.io/py/pandas.svg)](https://badge.fury.io/py/pandas) | [![PyPI version](https://badge.fury.io/py/statsmodels.svg)](https://badge.fury.io/py/statsmodels) |  [![PyPI version](https://badge.fury.io/py/scikit-learn.svg)](https://badge.fury.io/py/scikit-learn)

PROJECT IN ACTIVE DEVELOPMENT AS OF 6.5.17.  **Code and slides coming (check back in July)**

# Identifying Suspicious Transactions on the Bitcoin Transaction Network
Used Spark, Neo4j to train a clustering model for anomaly classification to detect suspicious transactions relative to known rogue transactions on the Bitcoin network (through 2014).

## Problem Statement
TBA

## Data 

[ELTE Bitcoin project website](http://webcache.googleusercontent.com/search?q=cache:oKk_QM210JEJ:www.vo.elte.hu/bitcoin/&num=1&hl=en&gl=us&strip=1&vwsrc=0)

## Analytical Approach

Will better explain the questions guiding analyses and a summary of the methods involved.

- TF-IDF Vectorizer --> Multinomial Naive Bayes Classifier
- CountVectorizer --> HDP --> LDA --> Clustering & Topic Modeling


## Tool Stack (more to come)

- AWS g2.8xlarge linux EC2 instance with a Neo4j Graph Database
- Jupyter notebook
- Python 3.5
- Spark Python API (PySpark)
- Sci-kit Learn
- Graphistry

Might include step by step series of examples that tell you have to get a development env running

## Visuals [In Development]
TBA


## Conclusions
More to come.  Will explain insights gleaned, model evaluation, or patterns in visualization.

```
Give an example
```

## Future Work

Ethereum LOL


## Author

* [**Andrew Tom**](https://github.com/Atomahawk)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments & Inspirations
- Flintrock is a command-line tool for launching Apache Spark clusters: https://github.com/nchammas/flintrock
- [Danny Luo](https://github.com/PiercingDan/spark-Jupyter-AWS) for the tutorial setting up spark clusters on AWS


