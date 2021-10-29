---
title: GeneralSimulationConfig
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.config](../index.html)/[GeneralSimulationConfig](index.html)



# GeneralSimulationConfig



[jvm]\
interface [GeneralSimulationConfig](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Simulation's configs valid for more than one simulation.



## Functions


| Name | Summary |
|---|---|
| [getDependencies](get-dependencies.html) | [jvm]<br>abstract fun [getDependencies](get-dependencies.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |
| [getEndStep](get-end-step.html) | [jvm]<br>abstract fun [getEndStep](get-end-step.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](get-end-time.html) | [jvm]<br>abstract fun [getEndTime](get-end-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Simulation's end time |
| [getLoader](get-loader.html) | [jvm]<br>abstract fun [getLoader](get-loader.html)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.html)<br>simulation's yaml as string |


## Inheritors


| Name |
|---|
| [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.html) |

