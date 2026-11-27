# Multi-Class-Classification-on-Dry-Bean-Dataset-Using-SVM-Kernels-and-Five-Gradient-Based-Optimizers
A multi-class classification project on the Dry Bean Dataset (13,611 samples, 16 numerical geometric/shape features, and 7 bean classes) comparing baseline Support Vector Machine (SVC) kernels against custom implementations of five optimization algorithms trained with Multi-Class Hinge Loss (Margin Loss) and L2 regularization across dedicated, modular notebooks.

Key Components & Workflow
Data Loading & Preprocessing

Loaded Dry_Bean_Dataset.xlsx (Dry_Beans_Dataset sheet), verified data shape, checked for missing values and duplicates, and inspected class distribution.

Encoded target classes with LabelEncoder, split data 80/20 using stratified sampling (stratify=y), and standardized features using StandardScaler.

Baseline SVM Kernels

Trained and evaluated SVC models using linear, poly, and rbf kernels on test accuracy, along with a classification_report for the top-performing kernel.

Custom Optimization Notebooks (GD, SGD, Mini-Batch GD, RMSprop, Adam)

Implemented multi-class hinge loss, margin calculation, and analytical gradients (dW, db) from scratch.

Built standalone 6-cell notebooks for GD, SGD, Mini-Batch GD, RMSprop, and Adam, tracking loss per epoch, training/test accuracy progression, and execution time.

Evaluation & Visualizations

Generated per-notebook visual diagnostics including Loss Curves, Train/Test Accuracy vs. SVM Kernel Benchmarks, and Test Confusion Matrices.
