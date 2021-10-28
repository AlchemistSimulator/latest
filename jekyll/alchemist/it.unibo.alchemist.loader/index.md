---
title: it.unibo.alchemist.loader
---
//[alchemist](../../index.html)/[it.unibo.alchemist.loader](index.html)



# Package it.unibo.alchemist.loader



## Types


| Name | Summary |
|---|---|
| [AlchemistModelProvider](-alchemist-model-provider/index.html) | [jvm]<br>interface [AlchemistModelProvider](-alchemist-model-provider/index.html)<br>Translates inputs to a Map representing the Alchemist model. |
| [EnvironmentAndExports](-environment-and-exports/index.html) | [jvm]<br>data class [EnvironmentAndExports](-environment-and-exports/index.html)<[T](-environment-and-exports/index.html), [P](-environment-and-exports/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](-environment-and-exports/index.html)>>(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](-environment-and-exports/index.html), [P](-environment-and-exports/index.html)>, **dataExtractors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../it.unibo.alchemist.loader.export/-extractor/index.html)>) : [InitializedEnvironment](-initialized-environment/index.html)<[T](-environment-and-exports/index.html), [P](-environment-and-exports/index.html)> <br>Pair-like implementation of [InitializedEnvironment](-initialized-environment/index.html). |
| [GraphStreamSupport](-graph-stream-support/index.html) | [jvm]<br>class [GraphStreamSupport](-graph-stream-support/index.html)<[T](-graph-stream-support/index.html), [P](-graph-stream-support/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](-graph-stream-support/index.html)>>(**linkingRule**: [LinkingRule](../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](-graph-stream-support/index.html), [P](-graph-stream-support/index.html)>, **deployment**: [Deployment](../it.unibo.alchemist.loader.deployments/-deployment/index.html)<[P](-graph-stream-support/index.html)>)<br>Support class for GraphStream, composed of a [linkingRule](-graph-stream-support/linking-rule.html) and a [deployment](-graph-stream-support/deployment.html). |
| [IllegalAlchemistYAMLException](-illegal-alchemist-y-a-m-l-exception/index.html) | [jvm]<br>open class [IllegalAlchemistYAMLException](-illegal-alchemist-y-a-m-l-exception/index.html) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)<br>This exception is thrown when the Alchemist YAML does not conform to the specification. |
| [InitializedEnvironment](-initialized-environment/index.html) | [jvm]<br>interface [InitializedEnvironment](-initialized-environment/index.html)<[T](-initialized-environment/index.html), [P](-initialized-environment/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](-initialized-environment/index.html)>><br>The result of the loading of an [environment](-initialized-environment/environment.html) with all the free variables instanced, also providing access to [dataExtractors](-initialized-environment/data-extractors.html). |
| [LoadAlchemist](-load-alchemist/index.html) | [jvm]<br>object [LoadAlchemist](-load-alchemist/index.html)<br>Loads Alchemist simulations from a variety of resources. |
| [Loader](-loader/index.html) | [jvm]<br>interface [Loader](-loader/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>An entity which is able to produce an Alchemist [InitializedEnvironment](-initialized-environment/index.html), resolving user defined variable values. |

