//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[LocalGeneralSimulationConfig](index.md)

# LocalGeneralSimulationConfig

[jvm]\
class [LocalGeneralSimulationConfig](index.md) : [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.md)

Local [GeneralSimulationConfig](../-general-simulation-config/index.md) that contains all information in local memory.

## Constructors

| | |
|---|---|
| [LocalGeneralSimulationConfig](-local-general-simulation-config.md) | [jvm]<br>open fun [LocalGeneralSimulationConfig](-local-general-simulation-config.md)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.md), endStep: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>Simulation's loader |
| [LocalGeneralSimulationConfig](-local-general-simulation-config.md) | [jvm]<br>open fun [LocalGeneralSimulationConfig](-local-general-simulation-config.md)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.md), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getEndStep](index.md#1508252319%2FFunctions%2F-267951372) | [jvm]<br>fun [getEndStep](index.md#1508252319%2FFunctions%2F-267951372)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](index.md#-529751618%2FFunctions%2F-267951372) | [jvm]<br>fun [getEndTime](index.md#-529751618%2FFunctions%2F-267951372)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Simulation's end time |
| [getLoader](index.md#1018251937%2FFunctions%2F-267951372) | [jvm]<br>fun [getLoader](index.md#1018251937%2FFunctions%2F-267951372)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.md)<br>simulation's yaml as string |

## Properties

| Name | Summary |
|---|---|
| [dependencies](dependencies.md) | [jvm]<br>private val [dependencies](dependencies.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>> |
