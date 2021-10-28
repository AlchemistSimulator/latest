//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[RemoteGeneralSimulationConfig](index.md)

# RemoteGeneralSimulationConfig

[jvm]\
class [RemoteGeneralSimulationConfig](index.md) : [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.md), [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)

Remote [GeneralSimulationConfig](../-general-simulation-config/index.md) that stores big informations in Ignite's cache.

## Constructors

| | |
|---|---|
| [RemoteGeneralSimulationConfig](-remote-general-simulation-config.md) | [jvm]<br>open fun [RemoteGeneralSimulationConfig](-remote-general-simulation-config.md)(sc: [GeneralSimulationConfig](../-general-simulation-config/index.md), ignite: Ignite)<br>A general simulation config to clone |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>open fun [close](close.md)() |
| [getDependencies](get-dependencies.md) | [jvm]<br>open fun [getDependencies](get-dependencies.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |
| [getEndStep](../-local-general-simulation-config/index.md#1508252319%2FFunctions%2F-267951372) | [jvm]<br>fun [getEndStep](../-local-general-simulation-config/index.md#1508252319%2FFunctions%2F-267951372)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](../-local-general-simulation-config/index.md#-529751618%2FFunctions%2F-267951372) | [jvm]<br>fun [getEndTime](../-local-general-simulation-config/index.md#-529751618%2FFunctions%2F-267951372)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Simulation's end time |
| [getLoader](../-local-general-simulation-config/index.md#1018251937%2FFunctions%2F-267951372) | [jvm]<br>fun [getLoader](../-local-general-simulation-config/index.md#1018251937%2FFunctions%2F-267951372)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.md)<br>simulation's yaml as string |
