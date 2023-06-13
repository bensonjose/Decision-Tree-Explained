# Decision-Tree-Explained

**What is a Decision Tree?<br>**
A decision tree is a flowchart-like tree structure where each internal node denotes the feature, branches denote the rules and the leaf nodes denote the result of the algorithm. <br>It is a versatile supervised machine-learning algorithm, which is used for both classification and regression problems.<br> It is one of the very powerful algorithms. <br>And it is also used in Random Forest to train on different subsets of training data, which makes random forest one of the most powerful algorithms in machine learning.<br>

**Decision Tree Terminologies**<br>
<br>

**Root Node:** It is the topmost node in the tree,  which represents the complete dataset. It is the starting point of the decision-making process.<br><br>
**Decision/Internal Node:** A node that symbolizes a choice regarding an input feature. Branching off of internal nodes connects them to leaf nodes or other internal nodes.<br><br>
**Leaf/Terminal Node:** A node without any child nodes that indicates a class label or a numerical value.<br><br>
**Splitting:** The process of splitting a node into two or more sub-nodes using a split criterion and a selected feature.<br><br>
**Branch/Sub-Tree:** A subsection of the decision tree starts at an internal node and ends at the leaf nodes.<br><br>
**Parent Node:** The node that divides into one or more child nodes.<br><br>
**Child Node:** The nodes that emerge when a parent node is split.<br><br>
**Impurity:** A measurement of the target variable’s homogeneity in a subset of data. It refers to the degree of randomness or uncertainty in a set of examples. The Gini index and entropy are two commonly used impurity measurements in decision trees for classifications task.<br><br>
**Variance:** Variance measures how much the predicted and the target variables vary in different samples of a dataset. It is used for regression problems in decision trees. Mean squared error, Mean Absolute Error, friedman_mse, or Half Poisson deviance are used to measure the variance for the regression tasks in the decision tree.<br><br>
**Information Gain:** Information gain is a measure of the reduction in impurity achieved by splitting a dataset on a particular feature in a decision tree. The splitting criterion is determined by the feature that offers the greatest information gain, It is used to determine the most informative feature to split on at each node of the tree, with the goal of creating pure subsets.<br><br>
**Pruning:** The process of removing branches from the tree that do not provide any additional information or lead to overfitting.<br><br>

![decision-tree-classification-algorithm](https://github.com/bensonjose/Decision-Tree-Explained/assets/90842204/0e9beddd-3f55-4d28-b6cc-b6d0b3d96bba)<br><br>


**Fig: Decision Tree Example**<br>
![decision_tree_for_heart_attack_prevention_2140bd762d](https://github.com/bensonjose/Decision-Tree-Explained/assets/90842204/77ef517f-d870-4d65-986e-71274f19f92b)
