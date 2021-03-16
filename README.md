# Islamov Rustem, Bachelor's degree Thesis
# Исламов Рустем, Бакалаврский диплом

## Theme: Distributed Second Order Methods with Fast Rates  and Compressed Communication.
## Тема: Распределенные методы второго порядка с быстрой скоростью сходимости и компрессией.

## Scientific supervisor: Peter Richtárik
## Научный руководитель: Питер Рихтарик

### Abstract:

We develop several new communication-efficient second-order methods for distributed optimization. Our first method, sf `NEWTON-STAR`, is a variant of Newton's method from which it inherits its fast local quadratic rate. However, unlike Newton's method, `NEWTON-STAR` enjoys the same per iteration communication cost as gradient descent. While this method is impractical as it relies on the use of certain unknown parameters characterizing the Hessian of the objective function at the optimum,  it serves as the starting point which enables us design practical variants thereof with strong theoretical guarantees. In particular, we design a stochastic sparsification strategy for learning the unknown parameters in an iterative fashion in a communication efficient manner. Applying this strategy to`NEWTON-STAR` leads to our next method, `NEWTON-LEARN`, for which we prove  local linear and superlinear rates independent of the condition number. When applicable, this method can have dramatically superior convergence behavior when compared to state-of-the-art methods. Finally, we develop a globalization strategy using cubic regularization which leads to our next method, `CUBIC-NEWTON-LEARN`, for which we prove global sublinear and linear convergence rates, and a fast superlinear rate. Our results are supported with experimental results on real datasets, and show several orders of magnitude improvement on baseline and state-of-the-art methods in terms of communication complexity.


### Аннотация:

Мы разработали несколько новых эффективных с точки зрения коммуникации методов второго порядка для распределенной оптимизации. Наш первый метод, `NEWTON-STAR`, является одним из вариантов метода Ньютона, от которого он наследует свою быструю локальную квадратичную скорость. Однако, в отличие от метода Ньютона, `NEWTON-STAR` имеет ту же стоимость коммуницирования за одну итерацию, что и градиентный спуск. Хотя этот метод непрактичен, поскольку он опирается на использование некоторых неизвестных параметров, характеризующих Гессиан целевой функции в оптимуме, он служит отправной точкой, которая позволяет нам проектировать практические варианты с доказанными теоретическими гарантиями сходимости. В частности, мы разрабатываем стратегию, основанную на использовании случайной разреженности для изучения неизвестных параметров итеративным способом, сохраняя эффективность с точки зрения коммуникаций. Применение этой стратегии к `NEWTON-STAR` приводит к нашему следующему методу, `NEWTON-LEARN`, для которого мы доказали локальные линейные и сверхлинейные скорости сходимости, не зависящие от числа обусловленности функции. Когда это применимо, этот метод может иметь значительно более высокое поведение сходимости по сравнению с современными методами. Наконец, мы разрабатываем стратегию глобализации с использованием кубической регуляризации, которая приводит к нашему следующему методу, `CUBIC-NEWTON-LEARN`, для которого мы доказали глобальные сублинейные и линейные скорости сходимости, а также быструю сверхлинейную скорость сходимости. Наши результаты подтверждаются экспериментальными результатами на реальных наборах данных и показывают улучшение на несколько порядков по сравнению с базовыми и современными методами с точки зрения эффективности коммуницирования.
