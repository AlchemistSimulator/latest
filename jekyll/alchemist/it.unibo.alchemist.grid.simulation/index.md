---
title: it.unibo.alchemist.grid.simulation
---
//[alchemist](../../index.html)/[it.unibo.alchemist.grid.simulation](index.html)



# Package it.unibo.alchemist.grid.simulation



## Types


| Name | Summary |
|---|---|
| [Complexity](-complexity/index.html) | [jvm]<br>interface [Complexity](-complexity/index.html)<br>An entity which represents a simulation's complexity. |
| [ComplexityImpl](-complexity-impl/index.html) | [jvm]<br>class [ComplexityImpl](-complexity-impl/index.html) : [Complexity](-complexity/index.html)<br>[Complexity](-complexity/index.html) implementation. |
| [RemoteResult](-remote-result/index.html) | [jvm]<br>interface [RemoteResult](-remote-result/index.html)<br>Result of [RemoteSimulation](-remote-simulation/index.html). |
| [RemoteResultImpl](-remote-result-impl/index.html) | [jvm]<br>class [RemoteResultImpl](-remote-result-impl/index.html) : [RemoteResult](-remote-result/index.html)<br>[RemoteResult](-remote-result/index.html) implementation. |
| [RemoteSimulation](-remote-simulation/index.html) | [jvm]<br>interface [RemoteSimulation](-remote-simulation/index.html)<[T](-remote-simulation/index.html)> : IgniteCallable<[RemoteResult](-remote-result/index.html)> <br>Alchemist simulation that will be executed in remote cluster's nodes. |
| [RemoteSimulationImpl](-remote-simulation-impl/index.html) | [jvm]<br>class [RemoteSimulationImpl](-remote-simulation-impl/index.html)<[T](-remote-simulation-impl/index.html), [P](-remote-simulation-impl/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](-remote-simulation-impl/index.html)>?> : [RemoteSimulation](-remote-simulation/index.html)<[T](-remote-simulation-impl/index.html)> <br>[RemoteSimulation](-remote-simulation/index.html) implementation for Apache Ignite. |
| [SimulationSet](-simulation-set/index.html) | [jvm]<br>interface [SimulationSet](-simulation-set/index.html)<br>Set of configs for remote simulations creation. |
| [SimulationSetImpl](-simulation-set-impl/index.html) | [jvm]<br>class [SimulationSetImpl](-simulation-set-impl/index.html) : [SimulationSet](-simulation-set/index.html)<br>[SimulationSet](-simulation-set/index.html) implementation. |

