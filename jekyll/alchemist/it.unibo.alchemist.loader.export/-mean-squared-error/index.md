---
title: MeanSquaredError
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[MeanSquaredError](index.html)



# MeanSquaredError



[jvm]\
class [MeanSquaredError](index.html)<[T](index.html)> : [Extractor](../-extractor/index.html)

Exports the Mean Squared Error for the concentration of some molecule, given another molecule that carries the correct result. The correct value is extracted from every node, then the provided UnivariateStatistic is applied to get a single, global correct value. Then, the actual value is extracted from every node, its value is compared (subtracted) to the computed correct value, it gets squared, and then logged.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [MeanSquaredError](-mean-squared-error.html) | [jvm]<br>open fun [MeanSquaredError](-mean-squared-error.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, localCorrectValueMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localCorrectValueProperty: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), statistics: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localValueMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), localValueProperty: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>expected value [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |


## Functions


| Name | Summary |
|---|---|
| [extractData](extract-data.html) | [jvm]<br>open fun <[T](extract-data.html)> [extractData](extract-data.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Extracts numeric properties from an environment. |
| [getNames](get-names.html) | [jvm]<br>open fun [getNames](get-names.html)(): ImmutableList<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>the name of the properties that this [Extractor](../-extractor/index.html) can provide |

