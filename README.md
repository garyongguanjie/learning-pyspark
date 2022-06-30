# Learning pyspark

Documenting my learnings of pyspark as I learn them.

This repository aims to enable data scientists, data engineers and machine learning engineers to get up to speed with pyspark.

✅ Zero Setup with colab\
✅ Step by step tutorials\
✅ Increasing difficulty of tutorials\
✅ Covers tabular, NLP and recommendation problems


Since I am new to spark/pyspark please submit a pull request or create an issue if you spot any error.

## Introduction

This notebook goes through the hello world for big data applications using both RDD and DataFrame API.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/introduction.ipynb)

## Pyspark Basic API walkthrough

This is the quick start for pyspark dataframe api.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/quickstart_df.ipynb)


This is the quick start for the pyspark pandas api. This api tries to support most features in the pandas dataframe api to make it easy to use for data scientist who are familiar with pandas. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/quickstart_ps.ipynb)

Personally most of the examples that I see online use the pyspark dataframe api rather than the 'pandas' api or the RDD api.

## Different APIs for ML modelling in documentation

There are two APIs for ML in pyspark namely one api for RDD and another api for pyspark DataFrame. 

Googling something like `pyspark svm` might give an API for the wrong type of data.

pyspark.**ml** -> DataFrame API

pyspark.**mllib** -> RDD API

## Titanic Example

How to use spark for simple tabular dataset on the classic titanic problem.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/titanic-example.ipynb)

## Basic NLP example

How to use spark for simple NLP problems.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/imdb-nlp-example.ipynb)

## Movie recommendation example

Pyspark for collaborative filtering using movie lens dataset.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garyongguanjie/learning-pyspark/blob/master/movie-recommendation-example.ipynb)
