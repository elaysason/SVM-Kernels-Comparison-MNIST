# SVM-Kernels-Comparison-MNIST
Commparing support vector machine vs. Radial basis function on the MNIST dataset


1. [General](#General)
    - [Background](#background)
2. [Installation](#installation)


## General
The algorithms learn per algorithm a training set of MISIT,the hand written digit database.It makes predictions of new set of digit (test set).

The MINSIT databse got digits from 0 to 9

The various classifiers try to learn the the different characteristics unique to each digit, thus matching the digits in the test set to the digit that best suits it.

### Background
SVM is a suprvised learning model that is used for classifiction and regression analsis. In order to so it creates a hyperlane or multipule ones and classifiction is detrimned by being below or above the hyperlane and can be using kerenels in order to change the layout of the data created. Expalnation of the used kernels:

* Linear Kernel - The basic kernel, it is one dimensional in nature.The best when there a large amount of features. It is way faster than the other kernels.Defined as F(x,y)=<x,y> where F is the decision boundary.
* Polinomal Kernel -It is a more generalized representation of the linear kernel and defined as F(x,x') = <img src="https://i.imgur.com/CHUawNB.png" width=50% height=50%>
* RBF Kernel - Very popular opition, usually used for non linear data. Defined as F(x,x') =  <img src="https://i.imgur.com/dDfidZg.png" width=60% height=60%>

## Installation
I will use google as an example, but similar process can be performed on other notebook editors
1. Open google Colab
2. Clone the project by:
	```
	!git clone https://github.com/elaysason/SVM-Kernels-Comparison-MNIST.git
	```
	<img src="https://i.imgur.com/1vM7SEb.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width=40% height=40% />

3. Now the folder is in your files on colab. simpily download the notebook as showed

	<img src="https://i.imgur.com/RbUBifH.png" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width=30% height=30% />
