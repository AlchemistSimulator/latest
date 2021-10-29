//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[MeanSquaredError](index.md)

# MeanSquaredError

[jvm]\
class [MeanSquaredError](index.md)<[T](index.md)> : [Extractor](../-extractor/index.md)

Exports the Mean Squared Error for the concentration of some molecule, given another molecule that carries the correct result. The correct value is extracted from every node, then the provided UnivariateStatistic is applied to get a single, global correct value. Then, the actual value is extracted from every node, its value is compared (subtracted) to the computed correct value, it gets squared, and then logged.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |

## Constructors

| | |
|---|---|
| [MeanSquaredError](-mean-squared-error.md) | [jvm]<br>open fun [MeanSquaredError](-mean-squared-error.md)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../-exporter/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, localCorrectValueMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localCorrectValueProperty: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), statistics: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localValueMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localValueProperty: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>expected value [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |

## Functions

| Name | Summary |
|---|---|
| [extractData](extract-data.md) | [jvm]<br>open fun <[T](extract-data.md)> [extractData](extract-data.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-exporter/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-exporter/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.md) | [jvm]<br>open fun [getNames](get-names.md)(): ImmutableList<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](../-extractor/index.md) can provide |
