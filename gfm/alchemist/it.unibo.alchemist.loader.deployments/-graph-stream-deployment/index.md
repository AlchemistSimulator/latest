//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.deployments](../index.md)/[GraphStreamDeployment](index.md)

# GraphStreamDeployment

[jvm]\
class [GraphStreamDeployment](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**createLinks**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **graphStreamSupport**: [GraphStreamSupport](../../it.unibo.alchemist.loader/-graph-stream-support/index.md)<*, [P](index.md)>) : [Deployment](../-deployment/index.md)<[P](index.md)> 

A deployment based on a [GraphStream](https://graphstream-project.org/) graph.

## Constructors

| | |
|---|---|
| [GraphStreamDeployment](-graph-stream-deployment.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [GraphStreamDeployment](-graph-stream-deployment.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offsetX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, layoutQuality: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, generatorName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg parameters: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))<br>Builds a new GraphStream-based deployment, given the nodeCount, whether or not the arcs of such graph shoud be links (createLinks), the generatorName (must be the name of a subclass of BaseGenerator), and its parameters. |
| [GraphStreamDeployment](-graph-stream-deployment.md) | [jvm]<br>fun <[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [GraphStreamDeployment](-graph-stream-deployment.md)(createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), graphStreamSupport: [GraphStreamSupport](../../it.unibo.alchemist.loader/-graph-stream-support/index.md)<*, [P](index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [forEach](index.md#-1888597325%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](index.md#-1888597325%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.md)>) |
| [getAssociatedLinkingRule](get-associated-linking-rule.md) | [jvm]<br>open override fun <[T](get-associated-linking-rule.md)> [getAssociatedLinkingRule](get-associated-linking-rule.md)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](get-associated-linking-rule.md), [P](index.md)>?<br>The [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md) associated with this [GraphStreamDeployment](index.md), or null if the deployment has been created without static linking. |
| [iterator](../-deployment/iterator.md) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.md)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.md)> |
| [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.md)> |
| [stream](../-deployment/stream.md) | [jvm]<br>open override fun [stream](../-deployment/stream.md)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.md)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.md) |
