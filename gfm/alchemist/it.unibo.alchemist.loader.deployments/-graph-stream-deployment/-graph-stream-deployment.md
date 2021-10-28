//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[GraphStreamDeployment](index.md)/[GraphStreamDeployment](-graph-stream-deployment.md)

# GraphStreamDeployment

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [GraphStreamDeployment](-graph-stream-deployment.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offsetX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, layoutQuality: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, generatorName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg parameters: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))

Builds a new GraphStream-based deployment, given the nodeCount, whether or not the arcs of such graph shoud be links (createLinks), the generatorName (must be the name of a subclass of BaseGenerator), and its parameters.

[jvm]\
fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [GraphStreamDeployment](-graph-stream-deployment.md)(createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), graphStreamSupport: [GraphStreamSupport](../../it.unibo.alchemist.loader/-graph-stream-support/index.md)<*, [P](index.md)>)
