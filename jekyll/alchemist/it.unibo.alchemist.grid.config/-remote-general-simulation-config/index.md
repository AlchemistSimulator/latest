---
title: RemoteGeneralSimulationConfig
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.config](../index.html)/[RemoteGeneralSimulationConfig](index.html)



# RemoteGeneralSimulationConfig



[jvm]\
class [RemoteGeneralSimulationConfig](index.html) : [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.html), [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)

Remote [GeneralSimulationConfig](../-general-simulation-config/index.html) that stores big informations in Ignite's cache.



## Constructors


| | |
|---|---|
| [RemoteGeneralSimulationConfig](-remote-general-simulation-config.html) | [jvm]<br>open fun [RemoteGeneralSimulationConfig](-remote-general-simulation-config.html)(sc: [GeneralSimulationConfig](../-general-simulation-config/index.html), ignite: Ignite)<br>A general simulation config to clone |


## Functions


| Name | Summary |
|---|---|
| [close](close.html) | [jvm]<br>open fun [close](close.html)() |
| [getDependencies](get-dependencies.html) | [jvm]<br>open fun [getDependencies](get-dependencies.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |
| [getEndStep](../-local-general-simulation-config/index.html#1508252319%2FFunctions%2F-134779887) | [jvm]<br>fun [getEndStep](../-local-general-simulation-config/index.html#1508252319%2FFunctions%2F-134779887)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](../-local-general-simulation-config/index.html#-529751618%2FFunctions%2F-134779887) | [jvm]<br>fun [getEndTime](../-local-general-simulation-config/index.html#-529751618%2FFunctions%2F-134779887)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Simulation's end time |
| [getLoader](../-local-general-simulation-config/index.html#1018251937%2FFunctions%2F-134779887) | [jvm]<br>fun [getLoader](../-local-general-simulation-config/index.html#1018251937%2FFunctions%2F-134779887)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.html)<br>simulation's yaml as string |

