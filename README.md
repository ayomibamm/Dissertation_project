# Exploring the Potential of Machine Learning and Deep Learning Prediction Models for Thyroid Disease
## Background
The thyroid gland is an important endocrine gland, responsible for the synthesis and release of hormones that help regulate the body’s metabolic rate, growth, and development. This process is controlled by a feedback loop so that an increase in the secretion of Thyroid-Stimulating Hormone (TSH) by the Thyrotropin-Releasing Hormone stimulates the production of the main hormones: Triiodothyronine and Thyroxine by the gland. The rise in the hormone levels causes an inhibition in the secretion of TSH. A disruption of the feedback regulation may lead to hyperthyroidism or hypothyroidism disease, both of which can cause debilitating symptoms. Due to the complexities of the diseases, research has shown that it takes an average of 4.5 years to diagnose the disorder. Consequently, machine learning and deep learning models’ predictive capabilities have been extensively explored as an accurate decision-support tool for clinicians to help hasten the diagnosis phase.

This study proposed an approach that implemented different feature selection methods such as Recursive Feature Elimination, Feature Importance, and Pearson Correlation to identify key variables required to improve the chosen algorithms: Random Forest, Bagging Meta-estimator Classifier, Extreme Gradient Boosting, CatBoost, and Convolutional Neural Network. Additionally, the Random Under sampling and Synthetic Minority Oversampling techniques were applied to the dataset to resolve data imbalance problems. This approach can predict hypothyroid, hyperthyroid, non-thyroidal illness syndrome (NTIS), and binding protein imbalance.

### Dataset 
https://www.kaggle.com/datasets/emmanuelfwerr/thyroid-disease-data

### Algorithms Implemented
Machine Learning: Random forest, Bagging meta estimator, CatBoost, XGBoost
Deep Learning: Convolutional Neural Network

### Result
The random forest classifier yielded the best accuracy, precision, and area under curve scores of 98%, corroborated by the K-fold cross-validation. On the other hand, the deep learning algorithm attained an accuracy score of 95%, the best for multiclass thyroid disease classification problems, in comparison to existing studies.
