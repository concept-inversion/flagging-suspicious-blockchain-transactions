Python  | Numpy | Pandas | Statsmodels | Sci-Kit Learn
--------|-----|-----|---------|------
[![PyPI](https://img.shields.io/badge/python-3.5-blue.svg)]() | [![PyPI version](https://badge.fury.io/py/numpy.svg)](https://badge.fury.io/py/numpy) | [![PyPI version](https://badge.fury.io/py/pandas.svg)](https://badge.fury.io/py/pandas) | [![PyPI version](https://badge.fury.io/py/statsmodels.svg)](https://badge.fury.io/py/statsmodels) |  [![PyPI version](https://badge.fury.io/py/scikit-learn.svg)](https://badge.fury.io/py/scikit-learn)

**Clean notebooks to be uploaded**

# Identifying Suspicious Transactions on the Bitcoin Transaction Network
Used Spark, Neo4j to train a clustering model for anomaly classification to detect suspicious transactions relative to known rogue transactions on the Bitcoin network (through 2014).

## Problem Statement
Despite the promising potential of the blockchain to enable the transfer of value over the internet, it remains rife with theft and fraud.  This project was a partial replication of the methods implemented by Zambre & Shah (2013) to perform unsupervised clustering of fraudulent transactions using various network quantities as features. I demonstrated how this could be done in batch processing at scale with PySpark and Spark MLlib.

## Data 

[ELTE Bitcoin project website](http://webcache.googleusercontent.com/search?q=cache:oKk_QM210JEJ:www.vo.elte.hu/bitcoin/&num=1&hl=en&gl=us&strip=1&vwsrc=0)

## Analytical Approach

Will better explain the questions guiding analyses and a summary of the methods involved.

- TF-IDF Vectorizer --> Multinomial Naive Bayes Classifier
- CountVectorizer --> HDP --> LDA --> Clustering & Topic Modeling


## Tool Stack (more to come)

- AWS c2.8xlarge linux EC2 instance with a Neo4j Graph Database
- Jupyter notebook
- Python 3.5
- Spark Python API (PySpark)
- GraphX
- Spark MLlib
- Sci-kit Learn
- PyGraphistry

Might include step by step series of examples that tell you have to get a development env running

## Visual

#### [Watch my PyGraphistry Visual Clustering Demo](https://youtu.be/VJgRxGeKTIw)
- Orange transactions (and nodes) are fraudulent transactions tracking the movement of money from known theft victims.
- Purple transactions (and nodes) are not associated with any known fraudulent transactions.
[![Watch my PyGraphistry Visual Demo](https://img.youtube.com/vi/VJgRxGeKTIw/0.jpg)](https://youtu.be/VJgRxGeKTIw)

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
- Zambre & Shah, 2013: http://snap.stanford.edu/class/cs224w-2013/projects2013/cs224w-030-final.pdf
- Flintrock is a command-line tool for launching Apache Spark clusters: https://github.com/nchammas/flintrock
- [Danny Luo](https://github.com/PiercingDan/spark-Jupyter-AWS) for the tutorial setting up spark clusters on AWS


