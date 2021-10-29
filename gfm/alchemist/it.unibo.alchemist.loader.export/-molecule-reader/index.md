//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[MoleculeReader](index.md)

# MoleculeReader

[jvm]\
class [MoleculeReader](index.md) : [Extractor](../-extractor/index.md)

Reads the value of a molecule and logs it.

## Constructors

| | |
|---|---|
| [MoleculeReader](-molecule-reader.md) | [jvm]<br>open fun [MoleculeReader](-molecule-reader.md)(molecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, filter: [FilteringPolicy](../-filtering-policy/index.md), aggregators: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)<br>the target molecule |

## Functions

| Name | Summary |
|---|---|
| [extractData](extract-data.md) | [jvm]<br>open fun <[T](extract-data.md)> [extractData](extract-data.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-exporter/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-exporter/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.md) | [jvm]<br>open fun [getNames](get-names.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](../-extractor/index.md) can provide |
