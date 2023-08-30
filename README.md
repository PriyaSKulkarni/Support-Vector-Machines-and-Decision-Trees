# Support-Vector-Machines-and-Decision-Trees
CSE-6363-001-MACHINE LEARNING under Manfred Huber: Support Vector Machines and Decision Trees

**Support Vector Machines:**
1. We begin by addressing linearly separable training data:
a) Formulating the optimization function and constraints for the linear maximum margin problem without regularization. Also, deriving the Lagrangian and its dual for the problem.
b) Performing 3 SMO algorithm iterations on the data. For each iteration, we select two α parameters, compute unconstrained α values, clip them, and calculate corresponding decision boundary values. Visualizing each iteration's result.

**Support Vector Machines with Gaussian Kernels:**
2. We consider mug material prediction using SVM with Gaussian Kernels:
a) Utilizing SVM solver (e.g., MATLAB's fitcsvm), we learn linear SVM parameters. We use C for regularization and show classification accuracy on test and training sets. We plot decision boundaries' projections in the 3D attribute space and identify support vectors.
b) We repeat the classification with Gaussian Kernels. We examine C and σ's impact on accuracy and overfitting. Comparing results with linear SVM and visualizing data points colored by class in the 3D space. Identifying support vectors.

**Decision Trees:**
3. Addressing the 3-class problem of material prediction using Decision Trees:
a) Illustrating construction steps for a 2-level decision tree using a single step lookahead search and maximum information gain as the criterion. Calculating entropy and decisions for each node. Limiting to 3 features and a smaller dataset for manual work.
b) Implementing a decision tree learner for the full problem, allowing trees with predetermined depths using the information gain criterion.
c) Splitting the dataset, deriving trees of depths 1 to 8 using training data, and evaluating accuracy for each tree on both training and test sets. Comparing results to identify overfitting depths.

In summary, we delve into Support Vector Machines, Gaussian Kernels, and Decision Trees for material prediction and classification problems, including optimizations, algorithms, and accuracy evaluations.
