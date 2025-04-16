# Support Vector Machines Using Stochastic Gradient Descent

##  Overview
This project explores the mathematical and practical implementation of Support Vector Machines (SVMs) optimized using **Stochastic Gradient Descent (SGD)**. It includes a theoretical foundation, algorithm implementation from scratch, and a comparison with built-in SVM tools.

##  Team Members
- Mohamed Ahmed  
- Abdulrahman Omar  
- Yasmin Hegy  
- Moamen Elsayed  
- Abdulrahman Khalid  

---

##  Abstract
Support Vector Machines (SVMs) are powerful supervised learning algorithms used in both classification and regression. This project provides:
- Mathematical derivation of the SVM objective function.
- Explanation of hinge loss and slack variables.
- Implementation of **Soft Margin SVM** using **SGD**.
- Comparison between custom SVM implementation and scikit-learn’s built-in SVM classifier.

---

##  Keywords
`Support Vector Machines`, `Stochastic Gradient Descent`, `Hinge Loss`, `Classification`, `Optimization`, `Machine Learning`

---

##  Methodology

###  Soft Margin SVM
- Handles non-linearly separable data using slack variables.
- Explains the **primal** and **dual formulations**.
- Introduces the **hinge loss** function and its role in optimization.
- Shows how the regularization parameter `C` balances margin and error.

###  SGD Optimization for SVM
- Efficient alternative to batch gradient descent.
- Performs updates using one sample at a time.
- Detailed explanation of gradients and update rules.

---

##  Experimental Setup
- Dataset: Subset of the Iris dataset (binary classification).
- Data split: 80% training / 20% testing.
- Learning rate: `0.001`
- Iterations: `2000`
- Tools: Python, NumPy, Matplotlib, scikit-learn

---

##  Results

| Model         | Accuracy |
|---------------|----------|
| Custom SVM    | 100%     |
| Built-in SVM  | 100%     |

Both models achieved perfect accuracy on the test set.

###  Confusion Matrix (Custom SVM)
- **True Positives (TP):** 12  
- **True Negatives (TN):** 8  
- **False Positives (FP):** 0  
- **False Negatives (FN):** 0  

###  Visualizations
- Bar plots comparing accuracies.
- Confusion matrix heatmaps for both models.
- Hyperplanes plotted for both custom and built-in SVMs.

---


##  Conclusion
- SVM with SGD is effective and efficient for large-scale problems.
- Custom SVM achieved similar performance to built-in tools.
- Highlights the trade-off between margin maximization and classification error.
- Recommends extending comparisons to other classifiers like Naive Bayes and PCA for broader evaluation.

---

##  Acknowledgments
We would like to thank:
- **Dr. Ahmed Abdelsamea** – for his constant support and supervision.
- **Eng. Hossam Fathy** and **Eng. Youssef Mohamed** – for their technical guidance.
- **Dr. Mayada** – for her foundational lecture slides.
- And our amazing team for the collaboration and hard work!
