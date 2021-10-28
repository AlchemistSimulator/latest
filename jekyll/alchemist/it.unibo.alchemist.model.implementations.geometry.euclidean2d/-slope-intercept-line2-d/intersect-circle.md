---
title: intersectCircle
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.html)/[SlopeInterceptLine2D](index.html)/[intersectCircle](intersect-circle.html)



# intersectCircle



[jvm]\
open override fun [intersectCircle](intersect-circle.html)(center: [P](index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.html)<[P](index.html)>



Intersects a line and a circle. Radius must be positive. Intersection is performed by plugging the line equation in the circle equation and solving the resulting quadratic equation. Circle equation: (x - [center](intersect-circle.html).x)^2 + (y - [center](intersect-circle.html).y)^2 = r^2. Line equation: y = [slope](slope.html) * x + [yIntercept](y-intercept.html) unless [isVertical](is-vertical.html), x = [xIntercept](x-intercept.html) otherwise.




