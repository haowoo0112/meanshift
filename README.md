{%hackmd SybccZ6XD %}
# Mean Shift, Mode Seeking, and Clustering

###### tags: `paper`

## Code
mp4 source: https://www.pexels.com/video/tourist-crossing-the-street-855565/

## Eesult
|1|2
|-|-
|![](https://i.imgur.com/Ar7MbSR.jpg)|![](https://i.imgur.com/ZRDd1wE.jpg)

## Downside
![](https://i.imgur.com/u4QJEaY.jpg =400x200)

##  INTRODUCT

Mean shift algorithm
- nonflat kernels are allowed
- points in data can be weighted
- shift can be performed on any subset of X, while the data set S stay the same

## GENERALIZING MEAN SHIFT

### Kernels

:::warning
DEFINITION 1

X: n-dimensional Euclidean space, $R^n$
$x_i$: ith component of $x\in X$
The norm of $x\in X$: nonnegative number. ex: $||x||^2 = \sum|x_i|^2$
The inner product of x and y in X: $<x, y> = \sum x_iy_i$

$K(x) = k(||x||^2)$

:::

### Mean Shift Algorithms

