# Machine-Learning
This repo is a compilation of the all the **Machine Learning** stuff covered during my first-year at IIT Gandhinagar

## The Overview
The compilation of six major works in **Machine Learning**, as accomplished during the **March - April 2023** at **Indian Institute of Technology
Gandhinagar**, is contained in this repository. The Jupyter Notebooks include topics ranging from **building and understanding**
several famous **clustering, dimensionality reduction models** from scratch to **fine tuning hyperparameters of a model** and finally building a
**Convolutional Neural Network**.

## EigenFaces and PCA
The [EigenFaces_MyPCA Notebook](EigenFaces_MyPCA.ipynb) and the [Eigenfaces_MyPCA PDF](Eigenfaces_MyPCA.pdf) started out as an exploration into understanding the **EigenFace
Algorithm** from scratch. Each step from **scaling the original data matrix** to finding the **eigenvectors** and **eigenvalues** of its **covariance matrix** have been covered in great detail with examples and commentary.

## Clustering and PCA
The [Clustering_PCA Notebook](Clustering_PCA.ipynb) and the [Clustering_PCA PDF](Clustering_PCA.pdf) consist of in-depth building up of the
**KMeans clustering** algorithm and the **dimensionality reduction technique : Principal Component Analysis (PCA)** from scratch. The **load_wine dataset** consisting of original **13 dimensions** had been reduced to **2 and 3 dimensions** using PCA and clustering had been performed on this low dimensional data. The Clusters and the Cluster Centers have been plotted for visual aid too.

## ML Scratch
The [ML_Scratch Notebook](ML_Scratch.ipynb) and the [ML_Scratch PDF](ML_Scratch.pdf) consist of the entire compilation of several Machine Learning models being created and fit-predicted. Several other algorithms like the **KMeans, KCenter, PCA, K Nearest Neighbour Classifier (KNN)** have been developed from the scratch. Several Linear Regressors and Classifier models have been touched upon viz. **Gaussian Naive Bayes, Support Vector Machines (SVM), and Decision Trees and Decision Boundaries.**

## HackRush '23 at IIT Gandhinagar
The [Stock ML File](Stock_ML.pdf) and the [Optuna Tuning File](Optuna_Tuning.pdf) are a compilation of the ML Challenge at the annual hackathon of IITGN held from 14th - 16th April 2023. The problem required to **predict the stock prices** of a test dataset. Looking at the randomised feature data, it was soon decided to go for **Regressor models** for the prediction. Several such models were train-tested manually to minimise the RMSE. Even going further for the **XGBooster Regressor**, its **hyperparameters** were **fine-tuned** using **Optuna**. **Time-Series Forcasting** using **FBProphet** was also applied. The whole analysis was done in collaboration with Kishan Ved and Kristopher Paul, also first-year UGs here at IITGN.

## The Convolutional Neural Network (CNN)
The [MNIST CNN Notebook](MNIST_CNN.ipynb) and the [MNIST CNN PDF](MNIST_CNN.pdf) showcases the building of a standard CNN using the **Keras Sequential Model**. The [MNIST handwritten digits](https://en.wikipedia.org/wiki/MNIST_database) data is explored for the analysis. A lot of exploration was done to understand the working of a neural network along with its convolutional stages using the kernels employed for pre image processing.
