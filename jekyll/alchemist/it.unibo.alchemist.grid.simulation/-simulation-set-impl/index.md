---
title: SimulationSetImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.simulation](../index.html)/[SimulationSetImpl](index.html)



# SimulationSetImpl



[jvm]\
class [SimulationSetImpl](index.html) : [SimulationSet](../-simulation-set/index.html)

[SimulationSet](../-simulation-set/index.html) implementation.



## Constructors


| | |
|---|---|
| [SimulationSetImpl](-simulation-set-impl.html) | [jvm]<br>open fun [SimulationSetImpl](-simulation-set-impl.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()genSimConfig: [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.html), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()simulationConfigs: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html)>)<br>Config's shared by all simulations of set |


## Functions


| Name | Summary |
|---|---|
| [computeComplexity](compute-complexity.html) | [jvm]<br>open fun [computeComplexity](compute-complexity.html)(): [Complexity](../-complexity/index.html)<br>complexity of one simulation |
| [getGeneralSimulationConfig](get-general-simulation-config.html) | [jvm]<br>open fun [getGeneralSimulationConfig](get-general-simulation-config.html)(): [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.html)<br>Config's shared by all simulations of set |
| [getSimulationConfigs](../-simulation-set/get-simulation-configs.html) | [jvm]<br>abstract fun [getSimulationConfigs](../-simulation-set/get-simulation-configs.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html)><br>List of configs that differentiate set's simulations |


## Properties


| Name | Summary |
|---|---|
| [simulationConfigs](simulation-configs.html) | [jvm]<br>private val [simulationConfigs](simulation-configs.html): ImmutableList<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html)> |

