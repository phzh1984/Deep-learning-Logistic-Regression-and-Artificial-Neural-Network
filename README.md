# Deep-learning-Logistic-Regression-and-Artificial-Neural-Network

Deep learning, logistic regression, and artificial neural networks are concepts in the field of machine learning and artificial intelligence. Let me provide an overview of each term and explain their relationships.

Deep Learning:

Definition: Deep learning is a subset of machine learning that involves neural networks with multiple layers (deep neural networks). It is inspired by the structure and function of the human brain's neural networks.

Architecture: Deep learning models consist of an input layer, one or more hidden layers, and an output layer. Each layer contains nodes (neurons), and connections between nodes have associated weights. Deep learning has shown remarkable success in tasks such as image and speech recognition, natural language processing, and many others.

Logistic Regression:

Definition: Logistic regression is a statistical method used for binary classification problems. Despite its name, it is a classification algorithm, not a regression algorithm.
Model: In logistic regression, the output is transformed using the logistic function (sigmoid function), mapping the input to a value between 0 and 1. This output is interpreted as the probability of belonging to a certain class. Logistic regression is simple yet effective, especially when the relationship between the input features and the output is approximately linear.

Artificial Neural Network (ANN):

Definition: An artificial neural network is a computational model inspired by the structure and function of biological neural networks. It is a fundamental building block of deep learning.

Architecture: An artificial neural network consists of interconnected nodes organized into layers. Input nodes receive data, hidden layers process the information, and output nodes produce the final result. The connections between nodes have associated weights that are adjusted during the training process. ANNs can have multiple hidden layers, making them capable of learning complex relationships.

Relationships:

Logistic Regression vs. Artificial Neural Network: Logistic regression is a simple linear model suitable for binary classification tasks with a relatively simple input-output relationship. On the other hand, artificial neural networks, particularly deep neural networks, can capture more complex patterns in data, making them suitable for a broader range of tasks, including those with non-linear relationships.

Deep Learning and Neural Networks: Deep learning encompasses the broader field of using neural networks with multiple layers. Artificial neural networks with more than one hidden layer are considered deep neural networks. Deep learning leverages the depth of these networks to automatically learn hierarchical features from data, enabling better representation learning and abstraction.

Logistic regression is a specific type of model used for binary classification, artificial neural networks are the foundational models for deep learning, and deep learning refers to the broader field that involves using deep neural networks for various tasks. The relationships lie in the evolution from simpler models like logistic regression to more complex models like deep neural networks as the complexity of the learning task increases.

Overview of the Data Set

We'll be utilizing the "sign language digits dataset" for this tutorial.

Within this dataset, there are 2062 images depicting sign language digits.

As you're aware, digits span from 0 to 9, resulting in 10 unique signs.

To streamline our tutorial, we'll initially focus solely on signs 0 and 1.

Within the dataset, sign zero corresponds to indexes 204 through 408, totaling 205 occurrences.

Similarly, sign one is represented by indexes 822 through 1027, totaling 206 occurrences. Hence, we'll use 205 samples from each class (labels).

Please note: The provision of 205 samples is quite limited for deep learning purposes. However, given the nature of this tutorial, the quantity is inconsequential.

Now, let's prepare our X and Y arrays. X represents the image array containing zero and one signs, while Y denotes the label array (0 and 1).
