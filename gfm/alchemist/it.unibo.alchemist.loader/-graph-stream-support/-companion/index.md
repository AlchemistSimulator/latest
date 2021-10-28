//[alchemist](../../../../index.md)/[it.unibo.alchemist.loader](../../index.md)/[GraphStreamSupport](../index.md)/[Companion](index.md)

# Companion

[jvm]\
object [Companion](index.md)

## Functions

| Name | Summary |
|---|---|
| [generateGraphStream](generate-graph-stream.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](generate-graph-stream.md), [P](generate-graph-stream.md) : [Position](../../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](generate-graph-stream.md)>> [generateGraphStream](generate-graph-stream.md)(environment: [Environment](../../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](generate-graph-stream.md), [P](generate-graph-stream.md)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offsetX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetZ: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, generatorName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "EuclideanRandom", uniqueId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, layoutQuality: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, is3D: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, vararg parameters: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [GraphStreamSupport](../index.md)<[T](generate-graph-stream.md), [P](generate-graph-stream.md)><br>Given an [environment](generate-graph-stream.md), the [nodeCount](generate-graph-stream.md) to be displaced, the GraphStream's [generatorName](generate-graph-stream.md) and the [parameters](generate-graph-stream.md) for its constructor, an identifier [uniqueId](generate-graph-stream.md), a [layoutQuality](generate-graph-stream.md), and possibly a flag to decide whether or not to compute z-dimensions [is3D](generate-graph-stream.md). |
