# Credit_Risk_Analysis

**Overview of the analysis:**

The purpose of this analysis is to apply machine learning to solve a real-world challenge: credit card risk.

This project consists of three technical analysis deliverables to predict credit risk listed below:

- Deliverable 1: Resampling Models
- Deliverable 2: The SMOTEENN Algorithm
- Deliverable 3: Ensemble Classifiers

**Results:**

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

- Naive Random Oversampling: Precision Score: 0.99 Recall: 0.66 F1: 0.79
<img width="451" alt="naive" src="https://user-images.githubusercontent.com/78699465/124819116-d71c0600-df39-11eb-813e-98984428c35b.png">



- SMOTE Oversampling: Precision Score: 0.99 Recall: 0.66 F1: 0.79
<img width="473" alt="smote" src="https://user-images.githubusercontent.com/78699465/124819287-0e8ab280-df3a-11eb-89de-e8c975e7ece2.png">



- Undersampling: Precision Score: 0.99 Recall: 0.40 F1: 0.57
<img width="454" alt="undersampling" src="https://user-images.githubusercontent.com/78699465/124819487-501b5d80-df3a-11eb-88e9-a67adf5d83e3.png">



- Combination (Over and Under) Sampling: Precision Score: 0.99 Recall: 0.58 F1: 0.73
<img width="451" alt="comboOverUnder" src="https://user-images.githubusercontent.com/78699465/124820333-5958fa00-df3b-11eb-8f02-62bc6670ba10.png">


- Balanced Random Forest Classifier: Precision Score: 0.99 Recall: 0.91 F1: 0.95
<img width="467" alt="balancedRandomForest" src="https://user-images.githubusercontent.com/78699465/124820047-00896180-df3b-11eb-9ffc-c83f5b4c9c1a.png">


- Easy Ensemble AdaBoost Classifier: Precision Score: 0.99 Recall: 0.94 F1: 0.97
<img width="464" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/78699465/124820246-3a5a6800-df3b-11eb-8660-69e1c8f71abf.png">



**Summary:**

- First, recommend using the Easy Ensemble Classifier. It has the highest balanced accuracy score, the highest precision scores, and the highest sensitivity scores of all the models.
- Next, I would recommend using the Balanced Random Forest Classifier.


