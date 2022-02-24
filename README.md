#Examining Heart Disease Classifiers
Problem Statement
The problem is that cardiovascular diseases are the leading cause of death globally. The World Health Organization estimates that 17.9 million people died from cardiovascular disease in 2019, representing 32% of all global deaths. 85% of the deaths caused by the cardiovascular system were due to heart attack and stroke. Cardiovascular disease causes 38% of premature deaths. Heart disease is a common ailment, and this dataset contains 11 features that may predict heart disease. This dataset will help develop an early detection classifier to help patients prevent heart failure.

# Dataset
The dataset has 918 data points and 11 features. The dataset is compiled from five different sources. Out of the 11 total features, four are numerical, and seven are categorical. There is no missing data. However, there are abnormal values for cholesterol for 18.7% of the data points. The odd data resulted in the removal of the cholesterol feature. Additionally, one data point was removed due to an abnormal heart rate value.

# Literature review
Three papers and one article were used as a reference for this project. Sharma et al. is a study that compared the performance of SVM, decision tree, naïve bayes, and random forest on the Cleveland Heart Disease Dataset. Gavhane et al. provide an evaluation of a multi-layer perceptron algorithm. The multi-layer perceptron algorithm will give a performance comparison to the other algorithms in the project. Shah et al. compare naïve bayes, decision tree, k nearest neighbor, and random forest performance on a heart disease dataset. Dan Berdikulov provides a reference for dealing with missing/poor quality data.

# Hypothesis
We think that XGBoost will provide the best predictor in this project. We believe that gradient boosting will give a better model because it will constantly improve its predecessors during training.

We also predict that removing the cholesterol Feature will result in significantly improved results. We believe this because there were many cholesterol values are 0. We think that having a significant amount of 0 cholesterol values (not biologically possible) will hurt the analysis.
