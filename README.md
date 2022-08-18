## Introduction

### Executive Summary

In this project we analyze data from 9000 consumers to understand credit card useage and behavior.  We apply unsupervised learning techniques (KMeans and PCA) to perform customer market segmentation and use deep learning (Autoencoder) to narrow down the number of clusters. Finally, we provide analysis throughout the project to better suggest a targetted marketing campaign.

### Goals and Objectives

Leveraging analytics and data science to gain a competitive advantage is tremendously useful for any company. A marketing department interested in launching campaigns will notice better results by utilizing data science to target specific consumers. The primary goal of this project is to analyze credit card data from 9000 consumers and apply an unsupervised learning technique to segment the market by clustering "types" of customers. Additional objectives include using KMeans learning algorithm to cluster shoppers based on their behaviors with a credit card, using principal component analysis to narrow it down to 2 components, and the attempt a deep learning technique to better refine our results.

My hope is that the results would enable any decision makers to launch targetted marketing campaignes so that they can experience better results.

<a id="data"></a>
### Data Source
We will be using a credit card dataset from Kaggle specifically designed for practicing clustering algorithms. It can be obtained below:

https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/download?datasetVersionNumber=1

It is unclear whether this is a fictional dataset or not. Since the goal of this project is to apply unsupervised algorithms and practice using deep learning techniques to perform market segmentation, this dataset is quite useful. I believe there are benefits to gathering your own data and practicing data cleaning and manipulation. While the focus of this project is on practicing algorithms, I elected to used an already curated dataset. I do have a entire project on data collection and manipulation titled **Mergers & Acquisition - Stock Price Prediction**

https://nbviewer.org/github/clozgil/Mergers-Acquisition-Stock-Price-Prediction/blob/main/Mergers%20%26%20Acquisition%20-%20Stock%20Price%20Prediction.ipynb

### Disclaimer and Note
All credit goes to Dr. Ryan Ahmed from McMaster Univesrity in Canada. I've enjoyed his work on using data science to solve business problems. This is my second project that follows some of the research and exercises he's done. It is merely my interpretation of his instruction.

**Additional Note**<br>
There are "Back to the Top Links" all throughout the project that, if viewed in nbviewer, should return you to the table of contents
