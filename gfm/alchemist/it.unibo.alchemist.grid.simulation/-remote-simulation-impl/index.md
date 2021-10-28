//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.simulation](../index.md)/[RemoteSimulationImpl](index.md)

# RemoteSimulationImpl

[jvm]\
class [RemoteSimulationImpl](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>?> : [RemoteSimulation](../-remote-simulation/index.md)<[T](index.md)> 

[RemoteSimulation](../-remote-simulation/index.md) implementation for Apache Ignite.

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [RemoteSimulationImpl](-remote-simulation-impl.md) | [jvm]<br>open fun [RemoteSimulationImpl](-remote-simulation-impl.md)(generalConfig: [GeneralSimulationConfig](../../it.unibo.alchemist.grid.config/-general-simulation-config/index.md), config: [SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md), masterNodeId: [UUID](https://docs.oracle.com/javase/8/docs/api/java/util/UUID.html))<br>General simulation config |

## Functions

| Name | Summary |
|---|---|
| [call](call.md) | [jvm]<br>open fun [call](call.md)(): [RemoteResult](../-remote-result/index.md) |
