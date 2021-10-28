---
title: SimulationSet
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.simulation](../index.html)/[SimulationSet](index.html)



# SimulationSet



[jvm]\
interface [SimulationSet](index.html)

Set of configs for remote simulations creation.



## Functions


| Name | Summary |
|---|---|
| [computeComplexity](compute-complexity.html) | [jvm]<br>abstract fun [computeComplexity](compute-complexity.html)(): [Complexity](../-complexity/index.html)<br>complexity of one simulation |
| [getGeneralSimulationConfig](get-general-simulation-config.html) | [jvm]<br>abstract fun [getGeneralSimulationConfig](get-general-simulation-config.html)(): [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.html)<br>Config's shared by all simulations of set |
| [getSimulationConfigs](get-simulation-configs.html) | [jvm]<br>abstract fun [getSimulationConfigs](get-simulation-configs.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html)><br>List of configs that differentiate set's simulations |


## Inheritors


| Name |
|---|
| [SimulationSetImpl](../-simulation-set-impl/index.html) |

