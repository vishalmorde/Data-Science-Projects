Objective: To build a predictive model for detecting credit card fraud using supervised and unsupervised Machine Learning and Deep Learning algorithms.

Data: Public dataset from Kaggle Challenge (https://www.kaggle.com/mlg-ulb/creditcardfraud). It has 284K samples and 30 independent variables.

Algorithms: Supervised ML - Random Forest, XGBoost, LightGBM with SMOTE (Synthetic Minority Oversampling TEchniques) for handling class imbalance Deep Learning-based Methods - AutoEncoders Unsupervised ML - Local Outlier Factor, Isolation Forest

Conclusion: Fraud detection is one of the most interesting and complex Machine Learning problems. Typically it involves extreme class imbalance which needs to be handled by techniques such as SMOTE. Also, credit card fraud is an ever-evolving beast like Hydra! If you cut one head, 2 other heads will grow back in its place! This means a supervised learning framework does not work well because the model performance deteriorates very quickly. Unsupervised anomaly detection algorithms such as Isolation Forest show a great potential to develop a more robust fraud detection system
