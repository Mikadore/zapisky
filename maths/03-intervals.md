# Intervals 
Intervals are a way to denote a continuous range, usually in $\R$.

An interval consists of two parts, the "start" and the "stop".
Both of these values are either:
## Open intervals
$$
    \cdots b)
$$
Meaning up to but *not* including $b$
## Closed Intervals
$$
    \cdots b\rangle
$$
Meaning up to and including $b$

Put together:
$$
\begin{aligned}
    \langle 1; 2\rangle &= \{x\in\R;1 \le x \le 2\} \\ 
    (1;2) &= \{x\in R; 1 < x < 2\} \\
    (1;2\rangle &= \{x\in R; 1 < x \le 2\} \\
    \langle1;2) &= \{x\in R; 1 \le x < 2\}
\end{aligned}
$$

## Infinity
Special values in intervals are infinity.
Even though infinity ($\infty$) is not a number,
we can use it in place of a number (with a sign) to mean "the rest" in
that "direction" (yes, this is highly unrigorous). As such, infinity can only ever be
in an open interval:
$$
    (-\infty;0\rangle = \R^-_0 = \{x \in \R; x \le 0\} 
$$

## Set operations on intervals
As intervals are sets in $\R$, we can apply every operation defined for a set 
to an interval.
$$
    \langle 1; 3) \cup (2; 5\rangle = \langle 1; 5\rangle 
$$

# The Absolute value
The absolute value, usually denoted $\vert x \vert$, or sometimes $abs(x)$,
is usually used to "disregard the sign". For numbers, this turns negatives into positives,
but keeps positives positive. In geometry, it is used to mean "distance", as negative distance doesn't make much sense.

## For reals
$$
    abs(x): \R \rightarrow \R^+_0 = \begin{cases} x & x \ge 0 \\ -x & x < 0\end{cases}
$$

This function is noteworthy, in that it is one of the most trivial 
example of a conditional function that is not a simple composition of binary/unary operators.

However, it is not very interesting.

## Negation of stateaments involving absolutes
