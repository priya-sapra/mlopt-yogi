# mlopt-yogi
Project on [YOGI Adaptive Method for Nonconvex Optimization](https://papers.nips.cc/paper/8186-adaptive-methods-for-nonconvex-optimization.pdf) for Machine Learning and Optimization course at Rensselaer Polytechnic Institute. This project addresses the disadvantages of current exponential moving average (EMA) adaptive methods for gradient descent and discusses the YOGI method suggested by the paper. We review the advantages, disadvantages, and emperical results from experiments of YOGI.

See our presentation [here](https://rpi.box.com/s/jeon4y0l19n4pvtgxlwldgjtcxbdkvcq)

### File breakdown:
* Algorithms_Implementation.ipynb: Comparison of YOGI, ADAM, and Adagrad adaptive methods in Multiclass Log. Regression, Fashion MNIST
* SVM_yogi.ipynb: Implementation of YOGI on l2-regularized SVM, using "a9a" UCI Adults Dataset
* Autoencoder_yogi.ipynb: Implementation of YOGI on autoencoder from HW6, using Fashion MNIST
* adaptive-methods-yogi.ipynb: Adapted code from Lecture 14 to compare other common First Order Methods & Yogi
* MLOPT-YOGI Final Presentation.pdf: Slide deck presentation
* MLOPT_Project_Problem_Set.pdf: Set of problems to solve/explore as part of pedagogical aspect
* Annotated Proof Outline.pdf: A rudimentary proof outline provided as a learning aid
* YOGI_lemma_proofs.pdf:  in-depth proof analysis of the lemmas used, to provide more intuition to the proofs
