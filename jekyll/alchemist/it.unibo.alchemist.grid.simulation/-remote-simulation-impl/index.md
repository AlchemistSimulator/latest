---
title: RemoteSimulationImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.simulation](../index.html)/[RemoteSimulationImpl](index.html)



# RemoteSimulationImpl



[jvm]\
class [RemoteSimulationImpl](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>?> : [RemoteSimulation](../-remote-simulation/index.html)<[T](index.html)> 

[RemoteSimulation](../-remote-simulation/index.html) implementation for Apache Ignite.



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [RemoteSimulationImpl](-remote-simulation-impl.html) | [jvm]<br>open fun [RemoteSimulationImpl](-remote-simulation-impl.html)(generalConfig: [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.html), config: [SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html), masterNodeId: [UUID](https://docs.oracle.com/javase/8/docs/api/java/util/UUID.html))<br>General simulation config |


## Functions


| Name | Summary |
|---|---|
| [call](call.html) | [jvm]<br>open fun [call](call.html)(): [RemoteResult](../-remote-result/index.html) |

