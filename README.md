# Optimization via Gradient Descent

solve the general optimization problem where, given a function \( f : \mathbb{R}^n \rightarrow \mathbb{R} \),  compute

\[
x^* = \arg \min_{x \in \mathbb{R}^n} f(x)
\]

In particular,  consider the situation where \( f(x) \) is at least differentiable, which implies that we can compute its gradient \( \nabla f(x) \).

 one of the most common way to approach is to use the Gradient Descent (GD) method, which is an iterative algorithm that, given an initial iterate \( x_0 \in \mathbb{R}^n \) and a positive parameter 
 called step size \( \alpha_k > 0 \) for each iteration, computes

\[
x_{k+1} = x_k - \alpha_k \nabla f(x_k)
\]
