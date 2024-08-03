
Optimization via Gradient Descent

solve the general optimization problem where, given a function f:Rn→Rf:Rn→R,  compute

x∗=arg minx∈Rnf(x)x∗=arg minx∈Rn​f(x)

In particular,  consider the situation where f(x) is at least differentiable, which implies that it can compute its gradient ∇f(x)

one of the most common ways to approach is to use the Gradient Descent (GD) method, which is an iterative algorithm that, given an initial iterate x0∈Rnx0​∈Rn and a positive parameter called step size αk>0 for each iteration, computes

xk+1=xk−αk∇f(xk)xk+1​=xk​−αk​∇f(xk​)
