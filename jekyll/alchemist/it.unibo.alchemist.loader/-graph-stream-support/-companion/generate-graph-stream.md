---
title: generateGraphStream
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.loader](../../index.html)/[GraphStreamSupport](../index.html)/[Companion](index.html)/[generateGraphStream](generate-graph-stream.html)



# generateGraphStream



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](generate-graph-stream.html), [P](generate-graph-stream.html) : [Position](../../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](generate-graph-stream.html)>> [generateGraphStream](generate-graph-stream.html)(environment: [Environment](../../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](generate-graph-stream.html), [P](generate-graph-stream.html)>, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offsetX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetZ: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, generatorName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "EuclideanRandom", uniqueId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, layoutQuality: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, is3D: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, vararg parameters: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [GraphStreamSupport](../index.html)<[T](generate-graph-stream.html), [P](generate-graph-stream.html)>



Given an [environment](generate-graph-stream.html), the [nodeCount](generate-graph-stream.html) to be displaced, the GraphStream's [generatorName](generate-graph-stream.html) and the [parameters](generate-graph-stream.html) for its constructor, an identifier [uniqueId](generate-graph-stream.html), a [layoutQuality](generate-graph-stream.html), and possibly a flag to decide whether or not to compute z-dimensions [is3D](generate-graph-stream.html).




