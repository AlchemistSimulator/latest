//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[GeneralSimulationConfig](index.md)

# GeneralSimulationConfig

[jvm]\
interface [GeneralSimulationConfig](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Simulation's configs valid for more than one simulation.

## Functions

| Name | Summary |
|---|---|
| [getDependencies](get-dependencies.md) | [jvm]<br>abstract fun [getDependencies](get-dependencies.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |
| [getEndStep](get-end-step.md) | [jvm]<br>abstract fun [getEndStep](get-end-step.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Simulation's end step |
| [getEndTime](get-end-time.md) | [jvm]<br>abstract fun [getEndTime](get-end-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Simulation's end time |
| [getLoader](get-loader.md) | [jvm]<br>abstract fun [getLoader](get-loader.md)(): [Loader](../../it.unibo.alchemist.loader/-loader/index.md)<br>simulation's yaml as string |

## Inheritors

| Name |
|---|
| [LightInfoGeneralSimulationConfig](../-light-info-general-simulation-config/index.md) |
