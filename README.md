### Cross Validation and Grid (numpy)
#### (Implementing k-fold cross validation using only numpy)

#### Cross Validation
Cross-validation is a model validation technique. It is usually used for algorithm fine tuning and along with gridsearch, it helps us find the best hyper-parameters for implementation.<br>

#### k-Fold
Is one of the technique for cross-validating information. This method is simple and very helpful when a limited amount of training data is available.<br>
To implement k-fold and Grid Search:
 1. Divide the training dataset in k-partitions (or folds).
 2. Train the model k-times for every hyper-parameter you want to evaluate, switching one of the partitions as 'testing' data, the rest as training. Keep track of the testing results.
 3. Choose the best hyper-parameters that in average give better results.
 
__In the following implementation we will just be creating k-Fold from scratch using lists and arrays.__
