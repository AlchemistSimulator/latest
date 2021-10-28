---
title: LightInfoGeneralSimulationConfig
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.config](../index.html)/[LightInfoGeneralSimulationConfig](index.html)



# LightInfoGeneralSimulationConfig



[jvm]\
abstract class [LightInfoGeneralSimulationConfig](index.html) : [GeneralSimulationConfig](../-general-simulation-config/index.html)

Abstract simulation config that contains small serializable informations.



## Constructors


| | |
|---|---|
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.html), endStep: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>Simulation's end step |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)) |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.html)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getDependencies](get-dependencies.html) | [jvm]<br>abstract fun [getDependencies](get-dependencies.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |


## Properties


| Name | Summary |
|---|---|
| [endStep](end-step.html) | [jvm]<br>private val [endStep](end-step.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [endTime](end-time.html) | [jvm]<br>private val [endTime](end-time.html): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [loader](loader.html) | [jvm]<br>private val [loader](loader.html): [Loader](../../it.unibo.alchemist.loader/-loader/index.html) |


## Inheritors


| Name |
|---|
| [RemoteGeneralSimulationConfig](../-remote-general-simulation-config/index.html) |
| [LocalGeneralSimulationConfig](../-local-general-simulation-config/index.html) |

