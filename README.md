# Heart-Disease

WHO announced that cardiovascular diseases is the top one killer over the world. There are seventeen million people died from it every year, especially heart disease. Prevention is better than cure. If we can evaluate the risk of every patient who probably has heart disease, that is, not only patients but also everyone can do something earlier to keep illness away.

This dataset is a real data including important features of patients. This time we will build the predictable model by various library like Decision Tree Classifier, AdaBoost, Xgboost, etc. Before predict the test dataset, use concept of crossvalid to find the optimised parameters. after that, the model can calculate the weight of each features, so we can easily understand which feature is more influent than others.

Confusion matrix is a common technique to figure out the accuracy of the model. From the standpoint of medicine, the recall rate is more important than precision rate because no one want to be misdiagnosed if the one actually have heart disease. So we will check the recall performance. After that, F1 Score and accuracy can help us evaluate the model, and then we'll explore the features if the model is good enough.
