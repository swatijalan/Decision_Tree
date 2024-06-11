# Decision_Tree

Decision tree

A decision tree is a supervised machine learning algorithm used for both classification and regression tasks. It is a popular and intuitive model that resembles a flowchart or tree-like structure.

Decision trees are used to make decisions or predictions by recursively splitting the dataset into subsets based on the most significant attributes or features.

Here's how a decision tree works:

Root Node: At the beginning, you have a single node called the "root node" that represents the entire dataset.

Splitting: The decision tree algorithm evaluates different attributes (features) and selects the one that, when used as a decision criterion, results in the best separation of the data into subsets. This process is repeated at each internal node of the tree.

Internal Nodes: Internal nodes in the tree represent decisions or conditions based on the chosen attribute. For example, if you were building a decision tree to classify animals, an internal node might ask, "Is it a mammal?"

Branches: Each branch emerging from an internal node represents one of the possible outcomes or values for that attribute. For instance, if the decision is based on whether an animal is a mammal, you would have two branches: "Yes" and "No."

Leaves (Terminal Nodes): The terminal nodes, often referred to as "leaves," represent the final classification or prediction. In the animal example, the leaves might specify the animal's species or group.

Recursive Process: The process of splitting the data into subsets and creating new internal nodes continues recursively until certain stopping criteria are met. These criteria might include a maximum depth for the tree, a minimum number of samples in a leaf node, or other factors.

Predictions: To make a prediction or classification for a new data point, you traverse the tree from the root node down to a leaf node, following the path that corresponds to the values of the attributes for that data point. The class or value associated with the leaf node is the final prediction.

Decision trees have several advantages, including simplicity and interpretability, as they closely resemble human decision-making processes.

Disadvantage - It casues overfitting Problem. - It doesn't work well for huge dataset.

Hence we go for Random forest for this(Bagging technique).

So, here on the dataset we are using decision Tree model.
