---
title: it.unibo.alchemist.grid.config
---
//[alchemist](../../index.html)/[it.unibo.alchemist.grid.config](index.html)



# Package it.unibo.alchemist.grid.config



## Types


| Name | Summary |
|---|---|
| [GeneralSimulationConfig](-general-simulation-config/index.html) | [jvm]<br>interface [GeneralSimulationConfig](-general-simulation-config/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Simulation's configs valid for more than one simulation. |
| [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.html) | [jvm]<br>abstract class [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.html) : [GeneralSimulationConfig](-general-simulation-config/index.html)<br>Abstract simulation config that contains small serializable informations. |
| [LocalGeneralSimulationConfig](-local-general-simulation-config/index.html) | [jvm]<br>class [LocalGeneralSimulationConfig](-local-general-simulation-config/index.html) : [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.html)<br>Local [GeneralSimulationConfig](-general-simulation-config/index.html) that contains all information in local memory. |
| [RemoteGeneralSimulationConfig](-remote-general-simulation-config/index.html) | [jvm]<br>class [RemoteGeneralSimulationConfig](-remote-general-simulation-config/index.html) : [LightInfoGeneralSimulationConfig](-light-info-general-simulation-config/index.html), [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)<br>Remote [GeneralSimulationConfig](-general-simulation-config/index.html) that stores big informations in Ignite's cache. |
| [SimulationConfig](-simulation-config/index.html) | [jvm]<br>interface [SimulationConfig](-simulation-config/index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Simulation's configs for only one simulation. |
| [SimulationConfigImpl](-simulation-config-impl/index.html) | [jvm]<br>class [SimulationConfigImpl](-simulation-config-impl/index.html) : [SimulationConfig](-simulation-config/index.html)<br>[SimulationConfig](-simulation-config/index.html) implementation. |

