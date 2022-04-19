# IBM_machine_learning_with_py
Coursera:
- course: Machine learning with python
- specialization: IBM AI engineering

# Week1 Intro to machine learning
- Study date: 2022-4-11
- Supervised learning v.s. Unsupervised learning

# Week2 Regression
- Study date: 2022-4-15 & 17
- Simple regression v.s. multiple regression
- Linear v.s. non-linear regression

- Simple linear regression
     - $\widehat{y}=\theta_{0}+\theta_{1} x_{1}$
    - calculate coefficent  $\theta_0$  $\theta_1$
        
        $\small\theta_1 = \cfrac{\sum_{i=1}^s(x_i-\bar{x})-(y_i-\bar{y})}{\sum_{i=1}^s(x_i-\bar{x})^2}$       $\small\theta_0 = \bar{y}-\theta_0\bar{x}$
- Evaluation metrics
    - $$M A E =\frac{1}{n} \sum_{j=1}^{n}\left|y_{j}-\hat{y}_{j}\right|$$
    - $$ M S E =\frac{1}{n} \sum_{i=1}^{n}\left(y_{i}-\hat{y}_{i}\right)^{2}$$
    - $$R M S E =\sqrt{\frac{1}{n} \sum_{j=1}^{n}\left(y_{j}-\hat{y}_{j}\right)^{2}}$$
    - $$R A E =\frac{\sum_{j=1}^{n}\left|y_{j}-\hat{y}_{j}\right|}{\sum_{j=1}^{n}\left|y_{j}-\bar{y}\right|}$$
    - $$R S E =\frac{\sum_{j=1}^{n}\left(y_{j}-\hat{y}_{j}\right)^{2}}{\sum_{j=1}^{n}\left(y_{j}-\bar{y}\right)^{2}} $$
    - $$R^{2} =1-R S E$$

- **Multiple linear regression**
    - $\widehat{y}=\theta_{0}+\theta_{1} x_{1}+\theta_{2} x_{2}+...++\theta_{n} x_{n}$
    - estimate $\theta$
        - linear algebra operations → takes a long time
        - optimization alogorithm → gradient descent → proper approach

## Non-Linear Regression

- Polynomial regression

    $\hat{y}=\theta_0+\theta_1x+\theta_2x^2 +\theta_3x^3$  
    
    transformed into linear regresson 
    
    $\hat{y}=\theta_0+\theta_1x_1+\theta_2x_2 +\theta_3x_3$ 

- non-linear regression