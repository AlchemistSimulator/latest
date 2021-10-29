---
title: Extractor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[Extractor](index.html)



# Extractor



[jvm]\
interface [Extractor](index.html)

An object that is able to extract numeric informations from an Alchemist [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html), given the current [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)[Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), the last [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html) executed and the current simulation step.



## Functions


| Name | Summary |
|---|---|
| [extractData](extract-data.html) | [jvm]<br>abstract fun <[T](extract-data.html)> [extractData](extract-data.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.html) | [jvm]<br>abstract fun [getNames](get-names.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](index.html) can provide |


## Inheritors


| Name |
|---|
| [Time](../-time/index.html) |
| [MeanSquaredError](../-mean-squared-error/index.html) |
| [MoleculeReader](../-molecule-reader/index.html) |
| [NumberOfNodes](../-number-of-nodes/index.html) |
| [ExecutionTime](../-execution-time/index.html) |

