//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[Point](index.md)

# Point

[jvm]\
class [Point](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> : [Deployment](../-deployment/index.md)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> 

A single node in a single point.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Constructors

| | |
|---|---|
| [Point](-point.md) | [jvm]<br>open fun [Point](-point.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>, x: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), y: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>The [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](../-deployment/get-associated-linking-rule.md)> [getAssociatedLinkingRule](../-deployment/get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../../it.unibo.alchemist.loader/-loader/get-default.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open fun [iterator](../-deployment/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.loader/-loader/get-default.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader/-loader/get-default.md)> |
| [stream](stream.md) | [jvm]<br>open fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |
