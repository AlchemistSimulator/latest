---
title: MoleculeReader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[MoleculeReader](index.html)



# MoleculeReader



[jvm]\
class [MoleculeReader](index.html) : [Extractor](../-extractor/index.html)

Reads the value of a molecule and logs it.



## Constructors


| | |
|---|---|
| [MoleculeReader](-molecule-reader.html) | [jvm]<br>open fun [MoleculeReader](-molecule-reader.html)(molecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), property: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, filter: [FilteringPolicy](../-filtering-policy/index.html), aggregators: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>)<br>the target molecule |


## Functions


| Name | Summary |
|---|---|
| [extractData](extract-data.html) | [jvm]<br>open fun <[T](extract-data.html)> [extractData](extract-data.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.html) | [jvm]<br>open fun [getNames](get-names.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](../-extractor/index.html) can provide |

