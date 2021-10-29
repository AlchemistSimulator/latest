//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[Deployment](index.md)

# Deployment

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [Deployment](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> : [Iterable](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Functions

| Name | Summary |
|---|---|
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAssociatedLinkingRule](get-associated-linking-rule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun <[T](get-associated-linking-rule.md)> [getAssociatedLinkingRule](get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](../../it.unibo.alchemist.loader.export/-extractor/extract-data.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.loader.export/-extractor/extract-data.md)> |
| [stream](stream.md) | [jvm]<br>abstract fun [stream](stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](index.md) |

## Inheritors

| Name |
|---|
| [FromGPSTrace](../-from-g-p-s-trace/index.md) |
| [Point](../-point/index.md) |
| [AbstractCloseTo](../-abstract-close-to/index.md) |
| [AbstractRandomDeployment](../-abstract-random-deployment/index.md) |
| [CircularArc](../-circular-arc/index.md) |
| [GraphStreamDeployment](../-graph-stream-deployment/index.md) |
| [Grid](../-grid/index.md) |
| [SpecificPositions](../-specific-positions/index.md) |
