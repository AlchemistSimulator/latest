//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[GeometricGradientRectangle](index.md)

# GeometricGradientRectangle

[jvm]\
class [GeometricGradientRectangle](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> : [Rectangle](../-rectangle/index.md)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> 

Distributes nodes geometrically within a rectangular shape.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [GeometricGradientRectangle](-geometric-gradient-rectangle.md) | [jvm]<br>open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), steps: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Use this constructor to displace multiple groups of devices with exponentially varied density along an axis. |
| [GeometricGradientRectangle](-geometric-gradient-rectangle.md) | [jvm]<br>open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Use this constructor to displace devices with an exponentially varied density along an axis. |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open fun [iterator](../-deployment/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-mean-squared-error/index.md)> |
| [stream](../-abstract-random-deployment/stream.md) | [jvm]<br>open fun [stream](../-abstract-random-deployment/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>abstract fun [stream](../-deployment/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |
