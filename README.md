# Training-ML---EUR-NanoX



#### Abstract
This training course enables the participants to reinforce their theoretical and practical knowledge in order to implement machine learning techniques for the data analysis. The main algorithms for prediction (supervised learning) are presented. Each method is first presented and commented on a theoretical level, and then illustrated on numerical experiments run with public datasets using R and/or  python/scikit-learn software.

#### Objective of the training
To present the main algorithms for supervised learning : linear models for regression and classification, Classification and Regression Tress, Random Forests, introduction to Neural Networks and Deep Learning and to use them with R and/or python/scikit-learn.


#### Target participants
This training session is for researchers, students, engineers who wish to reinforce or extend their theoretical background and practical knowledge on automatic data analysis by statistical learning algorithms.

#### Prerequisites

- Basic knowledge in statistics: elementary probability and statistics. 
- Basic knowledge in algorithmic and programming.
- **Install** Python 3.6 with [Anaconda](https://conda.io/docs/user-guide/install/download.html). 
- **Install** with `conda` the [Keras](https://keras.io/) library including [TensorFLow](https://www.tensorflow.org/).
- **Install** [R](https://cran.r-project.org/) and [Rstudio](https://rstudio.com/) and [IR kernel](https://irkernel.github.io/installation/) 
- Internet access during the sessions in order to get possible updates or to load additional libraries.

*Scientific contacts:*  [Béatrice Laurent-Bonneau](https://perso.math.univ-toulouse.fr/laurent/), [Olivier Roustant](https://olivier-roustant.fr/)

#### Program
Every day from 9h to 17h30. Morning: lecture; afternoon: hands-on sessions.

- **Day1 ML Introduction and Unsupervised learning**
	- General presentation of statistical machine learning 
	- [**Slides**](https://github.com/wikistat/MLTraining/blob/master/Slides/CERFACS-J0-2019.pdf)
	- Principal component analysis  
	- Agglomerative Hierarchical Clustering
	- k-means, k-medoids and variants, DBSCAN...
	- [**Slides**] 
  
	- **Tutorials** Execute successively the first [tutorial](https://github.com/wikistat/MLTraining/blob/master/Notebooks/Clustering/ML-Clustering.ipynb) and then the episodes one of each notebook: [Ozone](https://github.com/wikistat/MLTraining/blob/master/Notebooks/Ozone/ML-Tutorial-Ozone.ipynb),
	[Mars](https://github.com/wikistat/MLTraining/blob/master/Notebooks/Mars/ML-Tutorial-Mars.ipynb), [HAR](https://github.com/wikistat/MLTraining/blob/master/Notebooks/ML-Tutorial-IoT-Har.ipynb), [MNIST](https://github.com/wikistat/MLTraining/blob/master/Notebooks/MNIST/ML-Tutorial-MNIST.ipynb). The segmentation of an image of Mars by clustering algorithms is specific to the first day.
	- ***N.B.*** It would be too long to execute all notebooks. So you can choose then accordingly to your level and / or your field of interest. Their is a complexity progression from Ozone to MNIST.
- **Day2 Supervised learning 1 / 2**
	- k nearest neighbors
	- Gaussian linear model, logistic regression, model selection
	- Lasso et variants
	- Support Vector Machines
	- [**Slides**](https://github.com/wikistat/MLTraining/blob/master/Slides/CERFACS-J2-2019.pdf)
	- **Tutorials** Episodes two of: [Ozone](https://github.com/wikistat/MLTraining/blob/master/Notebooks/Ozone/ML-Tutorial-Ozone.ipynb), [HAR](https://github.com/wikistat/MLTraining/blob/master/Notebooks/HAR/ML-Tutorial-IoT-Har.ipynb), [MNIST](https://github.com/wikistat/MLTraining/blob/master/Notebooks/MNIST/ML-Tutorial-MNIST.ipynb)
- **Day3 Supervised learning 2 / 2**
	- Decision Trees
	- Bagging, Random Forests, Boosting
	- Neural networks, deep learning
	- [**Slides**](https://github.com/wikistat/MLTraining/blob/master/Slides/CERFACS-J3-BL-2019.pdf)
	- **Tutorials** Episodes three of: [Ozone](https://github.com/wikistat/MLTraining/blob/master/Notebooks/Ozone/ML-Tutorial-Ozone.ipynb), [HAR](https://github.com/wikistat/MLTraining/blob/master/Notebooks/HAR/ML-Tutorial-IoT-Har.ipynb), [MNIST](https://github.com/wikistat/MLTraining/blob/master/Notebooks/MNIST/ML-Tutorial-MNIST.ipynb)
- **Day4 Other ML algorithms**
	- Sequential learning, multi-armed bandit problems
	- Super-learning and expert aggregation
	- Reinforcement learning (introduction)
	- [**Slides**](https://github.com/wikistat/MLTraining/blob/master/Slides/CERFACS-J4-2019.pdf)
	- **Tutorials**[Inventory Control](https://github.com/wikistat/MLTraing/tree/master/Notebooks/home-local/pbesse/Documents/GitHub/MLTraining/Notebooks/inventoryControl.R)
	
*N.B.* Notebooks analysing many other use cases are available on [Wikistat](https://github.com/wikistat/).

