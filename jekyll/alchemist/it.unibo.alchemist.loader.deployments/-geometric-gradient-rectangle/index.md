---
title: GeometricGradientRectangle
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[GeometricGradientRectangle](index.html)



# GeometricGradientRectangle



[jvm]\
class [GeometricGradientRectangle](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../-circle/index.html)>?> : [Rectangle](../-rectangle/index.html)<[P](../-circle/index.html)> 

Distributes nodes geometrically within a rectangular shape.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |



## Constructors


| | |
|---|---|
| [GeometricGradientRectangle](-geometric-gradient-rectangle.html) | [jvm]<br>open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../-circle/index.html)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), steps: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Use this constructor to displace multiple groups of devices with exponentially varied density along an axis. |
| [GeometricGradientRectangle](-geometric-gradient-rectangle.html) | [jvm]<br>open fun [GeometricGradientRectangle](-geometric-gradient-rectangle.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../-circle/index.html)>, rng: RandomGenerator, nodes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizex: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sizey: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), lambda: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), horizontal: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), increasing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Use this constructor to displace devices with an exponentially varied density along an axis. |


## Functions


| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.html)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../-circle/index.html)> |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open fun [iterator](../-deployment/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../-circle/index.html)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)> |
| [stream](../-abstract-random-deployment/stream.html) | [jvm]<br>open fun [stream](../-abstract-random-deployment/stream.html)(): [Null](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-null/index.html)<br>abstract fun [stream](../-deployment/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../-circle/index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |

