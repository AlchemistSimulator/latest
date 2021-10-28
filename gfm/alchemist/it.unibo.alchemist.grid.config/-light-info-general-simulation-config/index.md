//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[LightInfoGeneralSimulationConfig](index.md)

# LightInfoGeneralSimulationConfig

[jvm]\
abstract class [LightInfoGeneralSimulationConfig](index.md) : [GeneralSimulationConfig](../-general-simulation-config/index.md)

Abstract simulation config that contains small serializable informations.

## Constructors

| | |
|---|---|
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.md), endStep: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>Simulation's end step |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.md), endTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)) |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md) | [jvm]<br>open fun [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config.md)(loader: [Loader](../../it.unibo.alchemist.loader/-loader/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getDependencies](get-dependencies.md) | [jvm]<br>abstract fun [getDependencies](get-dependencies.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>><br>Map with dependencies files path as key and their content as value |

## Properties

| Name | Summary |
|---|---|
| [endStep](end-step.md) | [jvm]<br>private val [endStep](end-step.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [endTime](end-time.md) | [jvm]<br>private val [endTime](end-time.md): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [loader](loader.md) | [jvm]<br>private val [loader](loader.md): [Loader](../../it.unibo.alchemist.loader/-loader/index.md) |

## Inheritors

| Name |
|---|
| [RemoteGeneralSimulationConfig](../-remote-general-simulation-config/index.md) |
| [LocalGeneralSimulationConfig](../-local-general-simulation-config/index.md) |
