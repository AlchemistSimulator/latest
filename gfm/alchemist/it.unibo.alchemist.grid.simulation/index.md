//[alchemist](../../index.md)/[it.unibo.alchemist.grid.simulation](index.md)

# Package it.unibo.alchemist.grid.simulation

## Types

| Name | Summary |
|---|---|
| [Complexity](-complexity/index.md) | [jvm]<br>interface [Complexity](-complexity/index.md)<br>An entity which represents a simulation's complexity. |
| [ComplexityImpl](-complexity-impl/index.md) | [jvm]<br>class [ComplexityImpl](-complexity-impl/index.md) : [Complexity](-complexity/index.md)<br>[Complexity](-complexity/index.md) implementation. |
| [RemoteResult](-remote-result/index.md) | [jvm]<br>interface [RemoteResult](-remote-result/index.md)<br>Result of [RemoteSimulation](-remote-simulation/index.md). |
| [RemoteResultImpl](-remote-result-impl/index.md) | [jvm]<br>class [RemoteResultImpl](-remote-result-impl/index.md) : [RemoteResult](-remote-result/index.md)<br>[RemoteResult](-remote-result/index.md) implementation. |
| [RemoteSimulation](-remote-simulation/index.md) | [jvm]<br>interface [RemoteSimulation](-remote-simulation/index.md)<[T](-remote-simulation/index.md)> : IgniteCallable<[RemoteResult](-remote-result/index.md)> <br>Alchemist simulation that will be executed in remote cluster's nodes. |
| [RemoteSimulationImpl](-remote-simulation-impl/index.md) | [jvm]<br>class [RemoteSimulationImpl](-remote-simulation-impl/index.md)<[T](-remote-simulation-impl/index.md), [P](-remote-simulation-impl/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](-remote-simulation-impl/index.md)>?> : [RemoteSimulation](-remote-simulation/index.md)<[T](-remote-simulation-impl/index.md)> <br>[RemoteSimulation](-remote-simulation/index.md) implementation for Apache Ignite. |
| [SimulationSet](-simulation-set/index.md) | [jvm]<br>interface [SimulationSet](-simulation-set/index.md)<br>Set of configs for remote simulations creation. |
| [SimulationSetImpl](-simulation-set-impl/index.md) | [jvm]<br>class [SimulationSetImpl](-simulation-set-impl/index.md) : [SimulationSet](-simulation-set/index.md)<br>[SimulationSet](-simulation-set/index.md) implementation. |
