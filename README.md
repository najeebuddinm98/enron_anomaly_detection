# Anomaly Detection on Enron Dataset

In this project, we aim to build and train models based on machine learning algorithms commonly used for unsupervised anomaly detection; namely 

* one-class Support Vector Machine (SVM)

* Isolation Forest

* Local Outlier Factor (LOF)

 The dataset used is a modified version of the Enron financial + email dataset that contains information about Enron Corporation, an energy, commodities, and services company that infamously went bankrupt in December 2001 as a result of fraudulent business practices.  The dataset we have obtained is from the [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) and their [GitHub](https://github.com/udacity/ud120-projects) page. Inspiration for loading and preprocessing the dataset was taken from Will Koehrsen's [Medium article](https://williamkoehrsen.medium.com/machine-learning-with-python-on-the-enron-dataset-8d71015be26d). 

The Enron dataset is widely used to try and develop models that can identify the persons of interests (POIs), i.e. individuals who were eventually tried for fraud or criminal activity in the Enron investigation, from the features within the data. The email + financial data contains the emails themselves, metadata about the emails such as number received by and sent from each individual, and financial information including salary and stock options.  

#### NOTE:
All references are presented in the form of appropriate hyperlinks within the paragraphs both here and in the notebook rather than in a separate section.