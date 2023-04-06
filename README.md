# Stroke-Prediction

Members: John Xiaoyu Zhang, Siling Liu

This project analyzes the information from a Stroke dataset to gain insights and better understanding of the data. We accomplish this through data processing, plotting, and exploring relationships between variables.

The dataset contains both categorical and numerical data, which vary among individuals. Some categorical variables, such as gender and residence type, are found to be irrelevant. However, age, heart disease, and average glucose level show some correlation with the occurrence of stroke. It is important to note that the data is imbalanced, with only a small proportion of stroke cases. This may lead to less accurate predictions when identifying stroke risk, but the analysis can still serve as a valuable reference for stroke prevention.

To address the issue of unbalanced data, we employed an oversampling strategy to increase the sample size of stroke cases in the training data.

We chose bagging, random forest, and neural network methods to train and predict our models. These approaches yielded favorable results, particularly for identifying individuals who are not at risk of stroke.
