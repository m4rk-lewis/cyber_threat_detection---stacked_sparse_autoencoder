# AWID Cyber threat detection using feature engineering (SSAE, PCA, UMAP, PHATE, SA, LLE, FA, LDA), Recursive Feature Elimination, Logistic Regression and Linear SVM classification (with Bayesian optimisation)


1) Download and Install libraries<br>
2) Mount Google Drive<br>
3) Load Data From CSV and Rename Class Variable<br>
<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/awid.jpg" width="500" title="dataset">
</p>
4) Initial Data Observations<br>
5) Pre-Processing Data<br>
6) Shuffle the Pandas Dataframe<br>
7) Pandas Dataset Split to NumPy (and empty the generated features dataframe)<br>
8) Stacked Sparse Autoencoder for Dimansionality Reduction and Feature Generation<br>
9) Stacked Sparse Autoencoder Optimisation using GridSearchCV<br>
10) PCA for Feature Generation<br>

<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/PCA.jpg" width="500" title="PCS">
</p>

11) UMAP for Feature Generation<br>
12) PHATE for Feature Generation<br>
13) Spectral Embedding for Feature Generation<br>
14) LocallyLinearEmbedding for Feature Generation<br>
15) Factor Analysis for Feature Generation<br>
16) LDA for Feature Generation<br>
17) Concatinate the generated features onto the original dataset<br>
18) Drop Features by Name (delete from generated features dataframe)<br>
19) Summary of Generated Feature Dataframe<br>
20) Reselect all generated features (undo Feature Selection)<br>
21) Feature Selection by Wrapper Method with RFE using LinearSVC / LogisticRegression / LinearDiscriminantAnalysis / RidgeClassifier<br>
22) Compare Classifier Models (unoptimised)<br>


<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/classification model selection.jpg" width="500" title="PCS">
</p>


<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/classification model selection - runtime.jpg" width="500" title="PCS">
</p>


23) LinearSVM Classifier BayesSearchCV Hyperparameter Optimisation<br>
24) Logistic Regression Classifier BayesSearchCV Hyperparameter Optimisation<br>
25) Logistic Regression Classifier (with Bayesian Optimisation)<br>

<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/Logistic Regression Classifier.jpg" width="500" title="PCS">
</p>

26) LinnearSVM Classifier (with Bayesian Optimisation)<br>

<p align="center">
  <img src="https://github.com/m4rk-lewis/cyber_threat_detection_using_stacked_sparse_autoencoder_LR_and_SVM/blob/main/pics/LinnearSVM Classifier.jpg" width="500" title="PCS">
</p>



