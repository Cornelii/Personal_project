# ImageNet Classification with Deep Convolutional Neural Networks
## - Alex Krizhevsky, * Geoffrey E. Hinton

* Hit the top at the LSVRC-2010 ?!
* Five Convolutional layers, max_pooling in some of those, three full-connected layers with a final 1000-way softmax (for 1000 classes.)


## I. Characteristics
#### 1. ReLu
$$ ReLu = max(x, 0) $$

#### 2. Local Response Normalization
$$
    \\b^{i}_{x,y} = a^{i}_{x,y} / (\kappa + \alpha \Sigma^{min(N-1, i+n/2)}_{j=max(0, i-n/2)}(a^{j}_{x,y})^2)^\beta
$$
$$
\begin{aligned}
\\\kappa, \alpha, \beta, n : hyperparameters
   \\i, x, y : position (x,y)\space at \space ith \space kernel 
\end{aligned}
$$


#### 3. Overlapping Pooling


## II. Architecture
