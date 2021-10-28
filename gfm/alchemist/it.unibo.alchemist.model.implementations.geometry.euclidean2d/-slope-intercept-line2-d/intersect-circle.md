//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d](../index.md)/[SlopeInterceptLine2D](index.md)/[intersectCircle](intersect-circle.md)

# intersectCircle

[jvm]\
open override fun [intersectCircle](intersect-circle.md)(center: [P](index.md), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Intersection2D](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-intersection2-d/index.md)<[P](index.md)>

Intersects a line and a circle. Radius must be positive. Intersection is performed by plugging the line equation in the circle equation and solving the resulting quadratic equation. Circle equation: (x - [center](intersect-circle.md).x)^2 + (y - [center](intersect-circle.md).y)^2 = r^2. Line equation: y = [slope](slope.md) * x + [yIntercept](y-intercept.md) unless [isVertical](is-vertical.md), x = [xIntercept](x-intercept.md) otherwise.
