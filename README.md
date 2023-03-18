# Gradient_Descent for 'Least Square Method'
 > As part of Optimization techniques for ML, I implemented gradient descent technique to optimize the objective 'Least sqaure function'. The goal is to predict height of a person from their weight (and gender) via linear regression. I have supplemented the analysis with data visualization employing correlation matrix and pairplots (via seaborn).
## Data-set I: Height Prediction form weight (and gender).
![alt text](https://github.com/108mk/Gradient_Descent/blob/b2515bc1b586957559f1273e554272f3d0390aad/demo-image/height_weight.png)

Model: Linear Regression.

### Data Visualization: PairPlot and Correlation plot

![alt text](https://github.com/108mk/Gradient_Descent/blob/646054004bb1605f50e99aff1e73f803e71577fb/demo-image/pair-plot.png)

![alt text](https://github.com/108mk/Gradient_Descent/blob/646054004bb1605f50e99aff1e73f803e71577fb/demo-image/gradient-descent_performance.png)

### Convergence Analysis: Two different learning rate ($\gamma$) gives drastically different converegence.

With $\gamma$ = 0.1 (Trial learning rate.)

![alt text](https://github.com/108mk/Gradient_Descent/blob/b2515bc1b586957559f1273e554272f3d0390aad/demo-image/L1.png)

With $\gamma = \frac{1}{L}$; where L is the Smoothness parameter of the optimized Least sqaure function.   

![alt text](https://github.com/108mk/Gradient_Descent/blob/b2515bc1b586957559f1273e554272f3d0390aad/demo-image/L2.png)
