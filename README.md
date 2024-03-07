## Bisection Method for Function Roots Calculation
### Explication of the method
The bisection method is based on the intermediate value theorem, which states that for any continuous function $f$ on a closed interval $[a,b]$, every value between $f(a)$ and $f(b)$  is the image of at least one value on that interval

If $f(a)$ and $f(b)$ have opposite signs, 0 would be a value between $f(a)$ and $f(b)$, so there is certainly at least one point $c$ that satisfies $f(c)=0$

To apply the bisection method, the following conditions must be met:
1. The function must be continuous.
2. The function values at the endpoints of the interval must have opposite signs.

The method consists of, given the conditions, take a midpoint between $a$ and $b$ (called $c$)
Calculate the value of $f(c)$ if the result is negative, replace $c$ by $a$ on the interval otherwise replace $c$ by $b$

With each new value "c" that we calculate in the function, we will either find the exact value of the root or obtain an approximate value.
