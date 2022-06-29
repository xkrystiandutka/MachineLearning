# Project II
## Implementing a classifier using the bagging method together with hard voting (but without using the class provided by scikit-learn!)

- Implementing a function that will generate bootstrap samples from a given dataset
- The function can additionally determine OOB data, i.e. those not used for training (e.g. by set difference or negation of indexing - pandas supports such miracles)
- Code that will add models (these can already come from scikit-learna) to some list
- Iterate through this list and train each model (each model is to be trained with a different bootstrap)
- Next function - testing. You can use the OOB data from point 1a or use a dedicated learning set 
- Last function - performing hard voting - again iterating over all models, generating a prediction and calculating the mod