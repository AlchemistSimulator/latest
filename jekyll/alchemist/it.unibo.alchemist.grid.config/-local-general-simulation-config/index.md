---
title: LocalGeneralSimulationConfig
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.config](../index.html)/[LocalGeneralSimulationConfig](index.html)



# LocalGeneralSimulationConfig



[jvm]\
class [LocalGeneralSimulationConfig](index.html) : [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.html)

Local [GeneralSimulationConfig](../-general-simulation-config/index.html) that contains all information in local memory.



## Constructors


| | |
|---|---|
| [LocalGeneralSimulationConfig](-local-general-simulation-config.html) | [jvm]<br>open fun [LocalGeneralSimulationConfig](-local-general-simulation-config.html)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.html), endStep: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>Simulation's loader |
| [LocalGeneralSimulationConfig](-local-general-simulation-config.html) | [jvm]<br>open fun [LocalGeneralSimulationConfig](-local-general-simulation-config.html)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getEndStep](index.html#1508252319%2FFunctions%2F-134779887) | [jvm]<br>fun [getEndStep](index.html#1508252319%2FFunctions%2F-134779887)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](index.html#-529751618%2FFunctions%2F-134779887) | [jvm]<br>fun [getEndTime](index.html#-529751618%2FFunctions%2F-134779887)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Simulation's end time |
| [getLoader](index.html#1018251937%2FFunctions%2F-134779887) | [jvm]<br>fun [getLoader](index.html#1018251937%2FFunctions%2F-134779887)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.html)<br>simulation's yaml as string |


## Properties


| Name | Summary |
|---|---|
| [dependencies](dependencies.html) | [jvm]<br>private val [dependencies](dependencies.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>> |

