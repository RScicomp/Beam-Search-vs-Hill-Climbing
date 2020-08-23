# Beam Search vs Hill Climbing
Here we evaluate the performance of Beam search and Hill Climbing. We see for almost every step size, the performance has increased using beam search, given that it does not get stuck in local maximums by providing k children at each iteration. Although in general, more steps are required for convergence when k
increases. 
<p align="center">
<img src="Formulas.png" width="250" height="70"/>
</p>
We would like to maximize these functions within the range of 0 ≤ 𝑥, 𝑦 ≤ 10. For each part below and each setting, we will report the mean and standard deviation of the number of steps to convergence and of the final value.

# Results

## Hill Climbing
<img src="Hill Climbing.png"/>

## Beam Search Formula 1
<img src="F2 Beam.png"/>

## Beam Search Formula 2
<img src="F1 Beam.png"/>
