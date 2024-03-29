### Decentralized Finite-Sum Optimization over Time-Varying Networks


In our numerical experiments, we consider a classification problem with different empirical risks, convex and nonconvex, respectively. If the dataset can be described as $(x_i, y_i)_{i=1}^n$, then:


- **Logistic regression loss**: $f(w) = \frac{1}{n}\sum\limits_{i=1}^n \ln \left(1 + e^{-y_i x_i^{\top}w}\right)$ with $y_i \in (-1, 1)$
  
- **Non-linear least squares loss**: $f(w) = \frac{1}{n}\sum\limits_{i=1}^n \left(y_i - 1/\left(1 + e^{-x_i^\top w}\right)\right)^2$ with $y_i \in (0, 1)$
