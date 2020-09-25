# Deadly car accidents in the Czech republic

Final (and winner) team project at the Data Science & Business intelligence Academy VŠE 2019/2020.

Our task was to find some open data, clean them, develop a classification or regression model, tune it, and interpret it.

We selected public data from the Czech police. Used the last 12 years. Merged all the files together (14 regions x 12 months x 12 years). Done some EDA, feature engineering, and lastly modeling.

For the label, we chose “Car accident had any deaths”. Therefore we went for the classification models. We tried different classifiers like logistic regression, decision tree, random forest, GBT, and Naive Bayes. For the sake of relative interpretation simplicity, we ended up with logit.

With the logit accuracy of 88%, the most significant predictor of whether the accidents were deadly was “Pedestrian collision”.
