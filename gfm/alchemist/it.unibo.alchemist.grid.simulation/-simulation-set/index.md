//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.simulation](../index.md)/[SimulationSet](index.md)

# SimulationSet

[jvm]\
interface [SimulationSet](index.md)

Set of configs for remote simulations creation.

## Functions

| Name | Summary |
|---|---|
| [computeComplexity](compute-complexity.md) | [jvm]<br>abstract fun [computeComplexity](compute-complexity.md)(): [Complexity](../-complexity/index.md)<br>complexity of one simulation |
| [getGeneralSimulationConfig](get-general-simulation-config.md) | [jvm]<br>abstract fun [getGeneralSimulationConfig](get-general-simulation-config.md)(): [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.md)<br>Config's shared by all simulations of set |
| [getSimulationConfigs](get-simulation-configs.md) | [jvm]<br>abstract fun [getSimulationConfigs](get-simulation-configs.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md)><br>List of configs that differentiate set's simulations |

## Inheritors

| Name |
|---|
| [SimulationSetImpl](../-simulation-set-impl/index.md) |
