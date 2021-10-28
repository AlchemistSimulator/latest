//[alchemist](../../index.md)/[it.unibo.alchemist.loader](index.md)

# Package it.unibo.alchemist.loader

## Types

| Name | Summary |
|---|---|
| [AlchemistModelProvider](-alchemist-model-provider/index.md) | [jvm]<br>interface [AlchemistModelProvider](-alchemist-model-provider/index.md)<br>Translates inputs to a Map representing the Alchemist model. |
| [EnvironmentAndExports](-environment-and-exports/index.md) | [jvm]<br>data class [EnvironmentAndExports](-environment-and-exports/index.md)<[T](-environment-and-exports/index.md), [P](-environment-and-exports/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](-environment-and-exports/index.md)>>(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](-environment-and-exports/index.md), [P](-environment-and-exports/index.md)>, **dataExtractors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../it.unibo.alchemist.loader.export/-extractor/index.md)>) : [InitializedEnvironment](-initialized-environment/index.md)<[T](-environment-and-exports/index.md), [P](-environment-and-exports/index.md)> <br>Pair-like implementation of [InitializedEnvironment](-initialized-environment/index.md). |
| [GraphStreamSupport](-graph-stream-support/index.md) | [jvm]<br>class [GraphStreamSupport](-graph-stream-support/index.md)<[T](-graph-stream-support/index.md), [P](-graph-stream-support/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](-graph-stream-support/index.md)>>(**linkingRule**: [LinkingRule](../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](-graph-stream-support/index.md), [P](-graph-stream-support/index.md)>, **deployment**: [Deployment](../it.unibo.alchemist.loader.deployments/-deployment/index.md)<[P](-graph-stream-support/index.md)>)<br>Support class for GraphStream, composed of a [linkingRule](-graph-stream-support/linking-rule.md) and a [deployment](-graph-stream-support/deployment.md). |
| [IllegalAlchemistYAMLException](-illegal-alchemist-y-a-m-l-exception/index.md) | [jvm]<br>open class [IllegalAlchemistYAMLException](-illegal-alchemist-y-a-m-l-exception/index.md) : [RuntimeException](https://docs.oracle.com/javase/8/docs/api/java/lang/RuntimeException.html)<br>This exception is thrown when the Alchemist YAML does not conform to the specification. |
| [InitializedEnvironment](-initialized-environment/index.md) | [jvm]<br>interface [InitializedEnvironment](-initialized-environment/index.md)<[T](-initialized-environment/index.md), [P](-initialized-environment/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](-initialized-environment/index.md)>><br>The result of the loading of an [environment](-initialized-environment/environment.md) with all the free variables instanced, also providing access to [dataExtractors](-initialized-environment/data-extractors.md). |
| [LoadAlchemist](-load-alchemist/index.md) | [jvm]<br>object [LoadAlchemist](-load-alchemist/index.md)<br>Loads Alchemist simulations from a variety of resources. |
| [Loader](-loader/index.md) | [jvm]<br>interface [Loader](-loader/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>An entity which is able to produce an Alchemist [InitializedEnvironment](-initialized-environment/index.md), resolving user defined variable values. |