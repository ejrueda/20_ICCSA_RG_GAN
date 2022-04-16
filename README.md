# 20_ICCSA_RG_GAN
## Description
New approach based on Generative Adversarial Network (GAN) and Support Vector Machine (SVM) to identify in-silico candidates for reference genes.<br /> The proposed method is divided into two main steps. First, the GAN is used to increase a small number of reference genes found in the public RNA-seq dataset of Escherichia coli. Second, a one-class SVM based on novelty detection is evaluated using some real reference genes and synthetic ones generated by the GAN architecture in the first step.<br />
The results show that increasing the dataset using the proposed GAN architecture improves the classifier score by 19%, making the proposed method have a recall score of 85% on the test data.
## Add some approaches for classification:
1) Change one class SVM parameters to achieve better results.<br />
2) Add Linear classifiers (Perceptron, Least square, Gradient descent, Widrow Hoff,etc).<br />
3) Add Parzen (Kernel density estimation), Gaussian mixture model for classification.<br />
4) Using Dimension reduction methods (Autoencoder, PCA) and classification of data with new dimensions.<br />
5) Add supervised mode (MLP and RBF network) with generate outlier data.<br />
## Paper
You can see paper at: https://link.springer.com/chapter/10.1007/978-3-030-58799-4_51

