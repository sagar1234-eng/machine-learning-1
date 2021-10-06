# machine-learning-1
**Aim of the Project:
The aim of the project is to build a Machine Learning Model to predict whether an owner will initiate an auto insurance claim in the next year.

The auto insurance industry is witnessing a paradigm shift. Since auto insurance company consists of homogenous good thereby making it difficult to differentiate product A from product B, also companies are fighting a price war (for insurance price). On top of that, the distribution channel is shifting more from traditional insurance brokers to online purchases,which means that the ability for companies to interact through human touchpoints is limited, and customers should be quoted at a reasonable price. A good price quote is one that makes the customer purchase the policy and helps the company to increase the profits. Also, the insurance premium is calculated based on more than 50+ parameters, which means that traditional business analytics-based algorithms are now limited in their ability to differentiate among customers based on subtle parameters.

**Process Flow:

The Machine Learningmodel mainly consist of two phases:

1.EDA (Exploratory Data Analysis): Analyze   the datasets   to   summarize   their   main characteristics(with  visual  methods).  A  statistical model  can  be  used,  primarily  EDA can be  used to see what  the  data  can  tell  us  beyond  the  formal modeling or hypothesis testing task.

Following tasks can be performed as a part of EDA:

(o) Scaling/Normalization

(o) Fill the missing values

(o)Feature selection & engineering.

2.Machine Learning Modeling:

After EDA, the modeling comes into the process. The process of training an ML model involves providing an ML algorithm (that is, the learning algorithm) with training data. The term “ML model” refers to the model artifact that is created by the training process.

Following tasks can be performed as a part of Modeling:

•Start with the basic model but eventually move towards ensemble

•Use  Deep  Learning  with  sklearn  MLPClassifier  and  check  if the Neural Network Model is better than traditional models

•Arrival at a model with best f1-score


MODELLING SUMMARY:

Finally after analyzing the various models, the XgBoost and Sklearn MLPClassifier model turned out to be best in classification with an accuracy and f1-score of 0.97-0.98.

The logistic model didn't performed well with both balanced and imbalanced dataset even after scaling and encoding categorical variables.The f1-score reached upto 0.58. It seems that the logistics regression is inefficient with dataset having large number of categorical feature.

Lastly, the Keras MLPClassifier need some hypertuning.
