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
## References
[1] G. J. Mahdi, “A Modified Support Vector Machine Classifiers Using Stochastic Gradient Descent with Application to Leukemia Cancer Type Dataset,” Baghdad Science Journal, vol. 17, no. 4. College of Science for Women, p. 1255, Dec. 01, 2020. doi:10.21123/bsj.2020.17.4.1255
[2] Cervantes, J., Garcia-Lamont, F., Rodríguez-Mazahua, L., & Lopez, A. (2020). A comprehensive survey on support vector machine classification: applications, challenges and trends.Neurocomputing.doi:10.1016/j.neucom.2019.10.118.
[3] H. Wang, J. Xiong, Z. Yao, M. Lin, and J. Ren, “Research Survey on Support Vector Machine,” Eudl, Jan. 2017, doi: 10.4108/eai.13-7-2017.2270596. 
[4]Y. Tian, Y. Shi, and X. Liu, “RECENT ADVANCES ON SUPPORT VECTOR MACHINES RESEARCH,” Technological and Economic Development of Economy, vol. 18, no. 1, pp. 5–33, Apr. 2012, doi: 10.3846/20294913.2012.661205.
[5] R. Guido, S. Ferrisi, D. Lofaro, and D. Conforti, “An Overview on the advancements of support vector machine models in healthcare Applications: a review,” Information, vol. 15, no. 4, p. 235, Apr. 2024, doi: 10.3390/info15040235.
[6]GeeksforGeeks. (2023, February 2). Introduction to Support Vector Machines (SVM). GeeksforGeeks.
[7]GeeksforGeeks. (2023b, August 1). ML | NonLinear SVM. GeeksforGeeks. 
[8] www.naukri.com, “Code 360 by Coding Ninjas,” 2024 Naukri.com. https://www.naukri.com/code360/library/combining-svm-sgd-in-machine-learning
[9]“1.5. Stochastic Gradient Descent,” Scikit-learn. https://scikit-learn.org/1.5/modules/sgd.html#sgd-mathematical-formulation
[10]“Breaking the Curse of Kernelization: Budgeted Stochastic Gradient Descent for Large-Scale SVM Training,” journal-article, Dec. 2012. [Online]. https://www.jmlr.org/papers/volume13/wang12b/wang12b.pdf
[11]S. Qaiser and R. Ali, “Text Mining: Use of TF-IDF to Examine the Relevance of Words to Documents,” International Journal of Computer Applications, vol. 181, no. 1, pp. 25–29, Jul. 2018, doi: 10.5120/ijca2018917395.
[12]Ingoampt, “Day 5 _ Mathematical Explanation behind SGD Algorithm in Machine Learning,” INGOAMPT, Jul. 16, 2024.
---

##  Acknowledgments
We would like to thank:
- **Dr. Ahmed Abdelsamea** – for his constant support and supervision.
- **Eng. Hossam Fathy** and **Eng. Youssef Mohamed** – for their technical guidance.
- **Dr. Mayada** – for her foundational lecture slides.
- And our amazing team for the collaboration and hard work!
