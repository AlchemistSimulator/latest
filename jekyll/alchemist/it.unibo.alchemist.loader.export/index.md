---
title: it.unibo.alchemist.loader.export
---
//[alchemist](../../index.html)/[it.unibo.alchemist.loader.export](index.html)



# Package it.unibo.alchemist.loader.export



## Types


| Name | Summary |
|---|---|
| [ExecutionTime](-execution-time/index.html) | [jvm]<br>class [ExecutionTime](-execution-time/index.html) : [Extractor](-extractor/index.html)<br>An extractor which provides informations about the running time of the simulation. |
| [Exporter](-exporter/index.html) | [jvm]<br>class [Exporter](-exporter/index.html)<[T](-exporter/index.html), [P](-exporter/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.loader.shapes/-circle/index.html)>?> : [OutputMonitor](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](../it.unibo.alchemist.loader.deployments/-deployment/get-associated-linking-rule.html), [P](../it.unibo.alchemist.loader.shapes/-circle/index.html)> <br>Writes on file data provided by a number of [Extractor](-extractor/index.html)s. |
| [Extractor](-extractor/index.html) | [jvm]<br>interface [Extractor](-extractor/index.html)<br>An object that is able to extract numeric informations from an Alchemist [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html), given the current [it.unibo.alchemist.core.interfaces.Simulation](../it.unibo.alchemist.core.interfaces/-simulation/index.html)[Time](../it.unibo.alchemist.model.interfaces/-time/index.html), the last [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.html) executed and the current simulation step. |
| [FilteringPolicy](-filtering-policy/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [FilteringPolicy](-filtering-policy/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Expresses a flat map operation over a double. |
| [MeanSquaredError](-mean-squared-error/index.html) | [jvm]<br>class [MeanSquaredError](-mean-squared-error/index.html)<[T](-mean-squared-error/index.html)> : [Extractor](-extractor/index.html)<br>Exports the Mean Squared Error for the concentration of some molecule, given another molecule that carries the correct result. |
| [MoleculeReader](-molecule-reader/index.html) | [jvm]<br>class [MoleculeReader](-molecule-reader/index.html) : [Extractor](-extractor/index.html)<br>Reads the value of a molecule and logs it. |
| [NumberOfNodes](-number-of-nodes/index.html) | [jvm]<br>class [NumberOfNodes](-number-of-nodes/index.html) : [Extractor](-extractor/index.html)<br>Logs the number of nodes in the scenario. |
| [StatUtil](-stat-util/index.html) | [jvm]<br>class [StatUtil](-stat-util/index.html)<br>Utility to translate statistics names into a UnivariateStatistic. |
| [Time](-time/index.html) | [jvm]<br>class [Time](-time/index.html) : [Extractor](-extractor/index.html)<br>Exports a column with the current time. |

