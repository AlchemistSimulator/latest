//[alchemist](../../index.md)/[it.unibo.alchemist.loader.export](index.md)

# Package it.unibo.alchemist.loader.export

## Types

| Name | Summary |
|---|---|
| [ExecutionTime](-execution-time/index.md) | [jvm]<br>class [ExecutionTime](-execution-time/index.md) : [Extractor](-extractor/index.md)<br>An extractor which provides informations about the running time of the simulation. |
| [Exporter](-exporter/index.md) | [jvm]<br>class [Exporter](-exporter/index.md)<[T](-exporter/index.md), [P](-exporter/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.loader.deployments/-circle/index.md)>?> : [OutputMonitor](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../it.unibo.alchemist.loader.deployments/-circle/index.md)> <br>Writes on file data provided by a number of [Extractor](-extractor/index.md)s. |
| [Extractor](-extractor/index.md) | [jvm]<br>interface [Extractor](-extractor/index.md)<br>An object that is able to extract numeric informations from an Alchemist [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md), given the current [it.unibo.alchemist.core.interfaces.Simulation](../it.unibo.alchemist.core.interfaces/-simulation/index.md)[Time](../it.unibo.alchemist.model.interfaces/-time/index.md), the last [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.md) executed and the current simulation step. |
| [FilteringPolicy](-filtering-policy/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [FilteringPolicy](-filtering-policy/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Expresses a flat map operation over a double. |
| [MeanSquaredError](-mean-squared-error/index.md) | [jvm]<br>class [MeanSquaredError](-mean-squared-error/index.md)<[T](-mean-squared-error/index.md)> : [Extractor](-extractor/index.md)<br>Exports the Mean Squared Error for the concentration of some molecule, given another molecule that carries the correct result. |
| [MoleculeReader](-molecule-reader/index.md) | [jvm]<br>class [MoleculeReader](-molecule-reader/index.md) : [Extractor](-extractor/index.md)<br>Reads the value of a molecule and logs it. |
| [NumberOfNodes](-number-of-nodes/index.md) | [jvm]<br>class [NumberOfNodes](-number-of-nodes/index.md) : [Extractor](-extractor/index.md)<br>Logs the number of nodes in the scenario. |
| [StatUtil](-stat-util/index.md) | [jvm]<br>class [StatUtil](-stat-util/index.md)<br>Utility to translate statistics names into a UnivariateStatistic. |
| [Time](-time/index.md) | [jvm]<br>class [Time](-time/index.md) : [Extractor](-extractor/index.md)<br>Exports a column with the current time. |
