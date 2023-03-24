<h1 align='center'>DIMENSIONALITY-REDUCTION-TECHNIQUES</h1>

<h2>INTRODUCTION </h2>

PCA is an unsupervised pre-processing task that is carried out before applying any ML algorithm. PCA is based on “orthogonal linear transformation” which is a mathematical technique to project the attributes of a data set onto a new coordinate system. The attribute which describes the most variance is called the first principal component and is placed at the first coordinate. Similarly, the attribute which stands second in describing variance is called a second principal component and so on. In short, the complete dataset can be expressed in terms of principal components. Usually, more than 90% of the variance is explained by two/three principal components. Principal component analysis, or PCA, thus converts data from high dimensional space to low dimensional space by selecting the most important attributes that capture maximum information about the dataset.

Linear Discriminant Analysis or Normal Discriminant Analysis or Discriminant Function Analysis is a dimensionality reduction technique that is commonly used for supervised classification problems. It is used for modelling differences in groups i.e. separating two or more classes. It is used to project the features in higher dimension space into a lower dimension space.  For example, we have two classes and we need to separate them efficiently. Classes can have multiple features. It works by calculating summary statistics for the input features by class label, such as the mean and standard deviation. These statistics represent the model learned from the training data. In practice, linear algebra operations are used to calculate the required quantities efficiently via matrix decomposition. LDA assumes that the input variables are numeric and normally distributed and that they have the same variance (spread). If this is not the case, it may be desirable to transform the data to have a Gaussian distribution and standardize or normalize the data prior to modeling.

<h2>OBJECTIVES </h2>

**- Perform PCA and LDA on Breast Cancer Dataset, write down your obsevations. While loading, use the toy dataset available in SKLearn (load_breast_cancer)**

**- Illustrate the effect of changing various method parameters of PCA and LDA. Compare the accuracies, and provide visualizations and interpretations for the evaluation metrices.**

**- "PCA could be used in applications such as Image Processing, to reduce the complexity of data and improve performance or to compress images". Justify this statement with your own findings.**


<h2>References </h2>

PCA

- https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html
- https://towardsdatascience.com/principal-component-analysis-for-breast-cancer-data-with-r-and-python-b312d28e911f
- https://www.kaggle.com/jahirmorenoa/pca-to-the-breast-cancer-data-set https://www.youtube.com/watch?v=e2sM7ccaA9c&ab_channel=DigitalSreeni
- https://www.datacamp.com/community/tutorials/principal-component-analysis-in-python
- https://towardsdatascience.com/dimensionality-reduction-of-a-color-photo-splitting-into-rgb-channels-using-pca-algorithm-in-python-ba01580a1118
- https://www.kaggle.com/mirzarahim/introduction-to-pca-image-compression-example
- https://github.com/gtraskas/breast_cancer_prediction/blob/master/breast_cancer.ipynb

LDA

- http://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.LinearDiscriminantAnalysis.html
- https://machinelearningmastery.com/linear-discriminant-analysis-with-python/
- https://towardsdatascience.com/linear-discriminant-analysis-in-python-76b8b17817c2
- https://www.mygreatlearning.com/blog/linear-discriminant-analysis-or-lda/
- https://www.geeksforgeeks.org/ml-linear-discriminant-analysis/

#


