//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[Extractor](index.md)

# Extractor

[jvm]\
interface [Extractor](index.md)

An object that is able to extract numeric informations from an Alchemist [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md), given the current [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)[Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), the last [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md) executed and the current simulation step.

## Functions

| Name | Summary |
|---|---|
| [extractData](extract-data.md) | [jvm]<br>abstract fun <[T](extract-data.md)> [extractData](extract-data.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.md) | [jvm]<br>abstract fun [getNames](get-names.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](index.md) can provide |

## Inheritors

| Name |
|---|
| [Time](../-time/index.md) |
| [MeanSquaredError](../-mean-squared-error/index.md) |
| [MoleculeReader](../-molecule-reader/index.md) |
| [NumberOfNodes](../-number-of-nodes/index.md) |
| [ExecutionTime](../-execution-time/index.md) |
