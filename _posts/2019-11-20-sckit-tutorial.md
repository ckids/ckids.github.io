---
layout: post
title:  "Scikit-learn Tutorial"
date:   2019-11-20 01:38:00 -0700
categories: [Scikit-learn, Python, Machine Learning, Jupyter, Parul Gupta]
---

### Scikit-learn
###### Author: Parul Gupta
---------------------------------------------------
Scikit-learn Python library implements a range of machine learning, preprocessing, cross validation and visualization algorithms using a unified interface. It focusses on modeling data not on loading and manipulating data. Some popular groups of models provided by scikit-learn include:
* **Clustering**: for grouping unlabeled data such as KMeans.
* **Cross Validation**: for performance estimation of supervised models on unseen data.
* **Datasets**: for test and generating datasets with specific properties for investigating model behavior.
* **Dimensionality Reduction**: for reducing the number of attributes in data for summarization, visualization and feature selection such as Principal component analysis.
* **Ensemble methods**: for combining the predictions of multiple supervised models.
* **Feature extraction**: for defining attributes in image and text data.
* **Feature selection**: for identifying meaningful attributes from which to create supervised models.
* **Parameter Tuning**: for getting the most out of supervised models.
* **Manifold Learning**: For summarizing and depicting complex multi-dimensional data.
* **Supervised Models**: a vast array not limited to generalized linear models, discriminate analysis, naive   bayes, lazy methods, neural networks, support vector machines and decision trees.

Scikit-learn come with a few standard datasets for exploration of different models provided, for instance the iris and digits datasets for classification and the boston house prices dataset for regression.

PS. Pro Tip : Scikit-learn is a great place to start as it provides access to high-quality, easy-to-use, implementations of popular algorithms.

### Installation (for Windows)
Install the 64bit version of Python 3, for instance from https://www.python.org. Then run:
```bash
$pip install –U scikit-learn
```
To verify your installation you can use:
```bash
$python -m pip show scikit-learn           # to see version and where scikit-learn is installed
$python -m pip freeze         # to see all packages installed
$python -c  "import sklearn; sklearn.show_versions()"
```
* Jupyter Notebook Tutorial: [sklearn-notebook.ipynb](https://nbviewer.jupyter.org/github/ckids/Jupyter-notebooks/blob/master/sklearn.ipynb)

### Below are the references to go deeper into Scikit.
1.	[Intro to Scikit-learn](https://machinelearningmastery.com/a-gentle-introduction-to-scikit-learn-a-python-machine-learning-library/)
2.	[Sklearn Classification](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
3.	[KNN with Scikit-learn](https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn)
4.	[Industries using Scikit-learn](https://scikit-learn.org/stable/testimonials/testimonials.html)
5.	[Loading an example dataset](https://scikit-learn.org/stable/tutorial/basic/tutorial.html#loading-an-example-dataset)
