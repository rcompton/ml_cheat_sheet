#Supervised learning superstitions cheat sheet

This notebook contains my notes and beliefs about several commonly-used supervised learning algorithms. My dream is that it will be useful as a quick reference or for people who are studying for machine learning interviews/quizzes/etc..

After some setup code, the methods discussed are:
+ Logistic regression
+ Decision trees
+ Support vector machines
+ K Nearest neighbors
+ Naive Bayes

To better understand each classifier we train on various versions of the "two moons" dataset and plot empirical decision boundaries. Each plot shows the training data on top of a few thousand randomly chosen points which have been colored by the output of the learned model. *Superstition #1:* The plots suggest that linear classifiers are often out performed on high quality training sets but still produce sane results on noisy small datasets. **Note: not all the plots have the same
xy dimensions.**

Other resources:
+ http://blog.echen.me/2011/04/27/choosing-a-machine-learning-classifier/ (good blog about choosing a classifier)
+ http://hunch.net/?p=22 (about overfitting)
+ http://www.dataschool.io/comparing-supervised-learning-algorithms/ (table of superstitions)
+ https://github.com/soulmachine/machine-learning-cheat-sheet (more like cheat 100 sheets)
+ http://scott.fortmann-roe.com/docs/BiasVariance.html (blog about the bias/variance problem)
