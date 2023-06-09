# Data_Analytics-1
Based on the code we have implemented, we are performing a decision tree analysis on a horse dataset. The goal of the analysis is to build a decision tree model that can predict the outcome of a horse based on various features or attributes.

The dataset contains information such as whether the horse had surgery, its age, rectal temperature, pulse rate, respiratory rate, mucous membrane color, capillary refill time, packed cell volume, total protein, and other related features. The target variable or outcome we are trying to predict is whether the horse lived or died.

Here's a breakdown of the analysis steps we have performed:

Data Cleaning: We initially cleaned the dataset to handle missing values and convert categorical variables into numerical representations.

Feature Selection: We used the chi-square test to perform feature selection and identify the most relevant features that have a significant association with the outcome.

Model Building: We built a decision tree classifier using scikit-learn's DecisionTreeClassifier. This classifier is trained on the dataset with both numerical and encoded categorical features.

Root Node Selection: We extracted the root node feature from the trained decision tree model. The root node represents the first split point in the decision tree, which is based on the most informative feature for predicting the outcome.

Decision Tree Visualization: We visualized the decision tree using the plot_tree() function from scikit-learn's tree module. This provides a graphical representation of the decision tree structure.

The overall objective of this analysis is to develop a decision tree model that can predict the outcome (whether a horse will live or die) based on the provided features. By analyzing the decision tree structure and the importance of different features, we can gain insights into the factors that contribute to the outcome and understand the decision-making process of the model. This can help in making informed decisions regarding horse healthcare, treatment, and prognosis.
