# Sentiment Analysis in AWS
First project in Machine Learning Nanodegree Udacity. 

## About
This repository is for deployment of a neural network to classify movie reviews. The architecture of the NN is a LSTM module with 200 hidden units and 32 dimensional embeddings followed by a fully-connected layer and a sigmoid.

The training is performed over the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

> Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In _Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies_. Association for Computational Linguistics, 2011.

## For Review

- SentimentAnalysis notebook: [pdf](SentimentAnalysis.pdf) or [html](SentimentAnalysis.html).
- [Web app (off)](website/index.html)
- [Questions and answers only.](Questions_only.html)  


Example using a review of "the emoji movie" taken from [insider](https://www.insider.com/) and that was written at [The Verge](https://www.theverge.com/).

<img src="Screenshot.png" alt="Screenshot" style="width: 100%;"/>


## Getting Started

You would need to clone this repository in a jupyter environment in SageMaker. Then open the jupyter notebook SageMaker Project.ipynb and follow it. Alternatively, you can have a look at a snapshot of the jupyter notebook in pdf: [SentimentAnalysis](SentimentAnalysis.pdf).

When deployed, [this webpage](website/index.html) should be working properly if the correct endpoint and API gateway are set up. You would need to modify the url in the post method!

## Requirements
In principle if it is run in AWS, the requirements are included in the folder train:

- pandas
- numpy
- nltk
- beautifulsoup4
- html5lib
