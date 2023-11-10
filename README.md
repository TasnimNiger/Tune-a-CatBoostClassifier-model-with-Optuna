# Tune-a-CatBoostClassifier-model-with-Optuna

![Leo](https://github.com/TasnimNiger/Tune-a-CatBoostClassifier-model-with-Optuna/assets/85071596/e4c02e18-505a-4a9b-b60e-c077719a860e)

**CatBoost** is an open source algorithm based on gradient boosted decision trees. CatBoost supports numerical, categorical, text, and embedding features.
Categorical features are used to build new numeric features based on categorical features and their combinations.

Hyper-Parameter Optimization is a difficult task. However, it can be made easier with tools like Optuna. Optuna is a hyperparameter tuning library to find the best hyperparameters for any tree-based model.
In this code we can see how to tune the hyper-parameters of a CatBoost model using Optuna.

**Key components of the framework:**

The optimization process in Optuna consists of minimizing/maximizing an objective function that takes a set of parameters as input and returns its score. This process is defined as study, whereas each objective function evaluation is called trial. The objective function is gradually built through the interaction with the trial object, while the search space is constructed dynamically by the object trial’s methods during the objective function runtime.

