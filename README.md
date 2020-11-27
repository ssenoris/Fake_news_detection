# Fake_news_detection
### Detecting fake news with LSTMs and Transformers (BERT)
======

## Introduction
====
Fake news is a news article that is intentionally and verifiably false that is produced online for a variety of purposes, such as financial and political gain with the dishonest intention of manipulating public opinion and/or being entertainment-oriented.
Detecting fake news on social media poses several new and challenging research problems. Its detection is very difficult due to fake news is intentionally written to mislead readers, which makes it nontrivial to detect simply based on news content. The content of fake news is rather diverse in terms of topics, styles and media platforms, and fake news attempts to distort truth with diverse linguistic styles while simultaneously mocking true news.
The extensive spread of fake news has the potential for extremely negative impacts on individuals and society. Therefore, fake news detection on social media has recently become an emerging research topic that is attracting tremendous attention. Fake news detection on social media presents unique characteristics and challenges which has led to the development of ingenious algorithms to approach them.


## Project details
====
The aim of this project is detecting fake news. The data is labeled as follows:

* "Barely-True"
* "False"
* "Half-True"
* "Mostly-True"
* "Not Known"
* "True"

The data set contains a column of text with the article and another one with the "tag" that describes it.

## Instructions
====

1. If you want to train the LSTM, execute the cells from the cell [1] to the cell [26].
	* You can directly load the model at the cell [33]
2. If you want to run Transformers run the cells from the point [51].
	* You can use function tranformation to chose different pretained models.

