# Islamov Rustem, Bachelor's degree Thesis
# Исламов Рустем, Бакалаврский диплом

## Theme: Distributed Second Order Methods with Fast Rates  and Compressed Communication.
## Тема: Распределенные методы второго порядка с быстрой скоростью сходимости и компрессией.

## Scientific supervisor: Peter Richtárik
## Научный руководитель: Питер Рихтарик

### Abstract:

We develop several new communication-efficient second-order methods for distributed optimization. Our first method, sf `NEWTON-STAR`, is a variant of Newton's method from which it inherits its fast local quadratic rate. However, unlike Newton's method, `NEWTON-STAR` enjoys the same per iteration communication cost as gradient descent. While this method is impractical as it relies on the use of certain unknown parameters characterizing the Hessian of the objective function at the optimum,  it serves as the starting point which enables us design practical variants thereof with strong theoretical guarantees. In particular, we design a stochastic sparsification strategy for learning the unknown parameters in an iterative fashion in a communication efficient manner. Applying this strategy to`NEWTON-STAR` leads to our next method, `NEWTON-LEARN`, for which we prove  local linear and superlinear rates independent of the condition number. When applicable, this method can have dramatically superior convergence behavior when compared to state-of-the-art methods. Finally, we develop a globalization strategy using cubic regularization which leads to our next method, `CUBIC-NEWTON-LEARN`, for which we prove global sublinear and linear convergence rates, and a fast superlinear rate. Our results are supported with experimental results on real datasets, and show several orders of magnitude improvement on baseline and state-of-the-art methods in terms of communication complexity.
