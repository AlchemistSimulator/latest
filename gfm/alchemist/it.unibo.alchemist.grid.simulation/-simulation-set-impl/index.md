//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.simulation](../index.md)/[SimulationSetImpl](index.md)

# SimulationSetImpl

[jvm]\
class [SimulationSetImpl](index.md) : [SimulationSet](../-simulation-set/index.md)

[SimulationSet](../-simulation-set/index.md) implementation.

## Constructors

| | |
|---|---|
| [SimulationSetImpl](-simulation-set-impl.md) | [jvm]<br>open fun [SimulationSetImpl](-simulation-set-impl.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()genSimConfig: [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.md), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()simulationConfigs: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md)>)<br>Config's shared by all simulations of set |

## Functions

| Name | Summary |
|---|---|
| [computeComplexity](compute-complexity.md) | [jvm]<br>open fun [computeComplexity](compute-complexity.md)(): [Complexity](../-complexity/index.md)<br>complexity of one simulation |
| [getGeneralSimulationConfig](get-general-simulation-config.md) | [jvm]<br>open fun [getGeneralSimulationConfig](get-general-simulation-config.md)(): [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.md)<br>Config's shared by all simulations of set |
| [getSimulationConfigs](../-simulation-set/get-simulation-configs.md) | [jvm]<br>abstract fun [getSimulationConfigs](../-simulation-set/get-simulation-configs.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md)><br>List of configs that differentiate set's simulations |

## Properties

| Name | Summary |
|---|---|
| [simulationConfigs](simulation-configs.md) | [jvm]<br>private val [simulationConfigs](simulation-configs.md): ImmutableList<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md)> |
