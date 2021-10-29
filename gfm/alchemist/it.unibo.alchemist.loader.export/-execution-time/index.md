//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[ExecutionTime](index.md)

# ExecutionTime

[jvm]\
class [ExecutionTime](index.md) : [Extractor](../-extractor/index.md)

An extractor which provides informations about the running time of the simulation.

## Functions

| Name | Summary |
|---|---|
| [extractData](extract-data.md) | [jvm]<br>open fun <[T](extract-data.md)> [extractData](extract-data.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-mean-squared-error/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-mean-squared-error/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.md) | [jvm]<br>open fun [getNames](get-names.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](../-extractor/index.md) can provide |
