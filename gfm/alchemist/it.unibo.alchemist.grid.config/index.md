//[alchemist](../../index.md)/[it.unibo.alchemist.grid.config](index.md)

# Package it.unibo.alchemist.grid.config

## Types

| Name | Summary |
|---|---|
| [GeneralSimulationConfig](-general-simulation-config/index.md) | [jvm]<br>interface [GeneralSimulationConfig](-general-simulation-config/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Simulation's configs valid for more than one simulation. |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.md) | [jvm]<br>abstract class [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.md) : [GeneralSimulationConfig](-general-simulation-config/index.md)<br>Abstract simulation config that contains small serializable informations. |
| [LocalGeneralSimulationConfig](-local-general-simulation-config/index.md) | [jvm]<br>class [LocalGeneralSimulationConfig](-local-general-simulation-config/index.md) : [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.md)<br>Local [GeneralSimulationConfig](-general-simulation-config/index.md) that contains all information in local memory. |
| [RemoteGeneralSimulationConfig](-remote-general-simulation-config/index.md) | [jvm]<br>class [RemoteGeneralSimulationConfig](-remote-general-simulation-config/index.md) : [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.md), [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)<br>Remote [GeneralSimulationConfig](-general-simulation-config/index.md) that stores big informations in Ignite's cache. |
| [SimulationConfig](-simulation-config/index.md) | [jvm]<br>interface [SimulationConfig](-simulation-config/index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Simulation's configs for only one simulation. |
| [SimulationConfigImpl](-simulation-config-impl/index.md) | [jvm]<br>class [SimulationConfigImpl](-simulation-config-impl/index.md) : [SimulationConfig](-simulation-config/index.md)<br>[SimulationConfig](-simulation-config/index.md) implementation. |
