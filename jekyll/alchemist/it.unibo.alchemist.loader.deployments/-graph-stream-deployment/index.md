---
title: GraphStreamDeployment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.deployments](../index.html)/[GraphStreamDeployment](index.html)



# GraphStreamDeployment



[jvm]\
class [GraphStreamDeployment](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**createLinks**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **graphStreamSupport**: [GraphStreamSupport](../../it.unibo.alchemist.loader/-graph-stream-support/index.html)<*, [P](index.html)>) : [Deployment](../-deployment/index.html)<[P](index.html)> 

A deployment based on a [GraphStream](https://graphstream-project.org/) graph.



## Constructors


| | |
|---|---|
| [GraphStreamDeployment](-graph-stream-deployment.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [GraphStreamDeployment](-graph-stream-deployment.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, randomGenerator: RandomGenerator, nodeCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), offsetX: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, offsetY: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, layoutQuality: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true, generatorName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg parameters: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html))<br>Builds a new GraphStream-based deployment, given the nodeCount, whether or not the arcs of such graph shoud be links (createLinks), the generatorName (must be the name of a subclass of BaseGenerator), and its parameters. |
| [GraphStreamDeployment](-graph-stream-deployment.html) | [jvm]<br>fun <[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [GraphStreamDeployment](-graph-stream-deployment.html)(createLinks: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), graphStreamSupport: [GraphStreamSupport](../../it.unibo.alchemist.loader/-graph-stream-support/index.html)<*, [P](index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [forEach](index.html#-1888597325%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](index.html#-1888597325%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [P](index.html)>) |
| [getAssociatedLinkingRule](get-associated-linking-rule.html) | [jvm]<br>open override fun <[T](get-associated-linking-rule.html)> [getAssociatedLinkingRule](get-associated-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](get-associated-linking-rule.html), [P](index.html)>?<br>The [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html) associated with this [GraphStreamDeployment](index.html), or null if the deployment has been created without static linking. |
| [iterator](../-deployment/iterator.html) | [jvm]<br>open operator override fun [iterator](../-deployment/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[P](index.html)> |
| [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../-close-to-g-p-s-trace/index.html#-1387152138%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[P](index.html)> |
| [stream](../-deployment/stream.html) | [jvm]<br>open override fun [stream](../-deployment/stream.html)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[P](index.html)><br>a [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) over the positions of this [Deployment](../-deployment/index.html) |

