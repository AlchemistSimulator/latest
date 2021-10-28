---
title: it.unibo.alchemist.core.interfaces
---
//[alchemist](../../index.html)/[it.unibo.alchemist.core.interfaces](index.html)



# Package it.unibo.alchemist.core.interfaces



[jvm]\
This package contains the interfaces to implement in order to create an engine.



## Types


| Name | Summary |
|---|---|
| [DependencyGraph](-dependency-graph/index.html) | [jvm]<br>interface [DependencyGraph](-dependency-graph/index.html)<[T](-dependency-graph/index.html)><br>This interface allows to separate the usage of a dependency graph from its implementation. |
| [Scheduler](-scheduler/index.html) | [jvm]<br>interface [Scheduler](-scheduler/index.html)<[T](-scheduler/index.html)><br>The type which describes the concentration of a molecule This interface is meant to be implemented by the data structure(s) which must manage the reactions. |
| [Simulation](-simulation/index.html) | [jvm]<br>interface [Simulation](-simulation/index.html)<[T](-simulation/index.html), [P](-simulation/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>?> : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html)<br>This interface forces simulations to be independent threads, and make them controllable from an external console. |
| [Status](-status/index.html) | [jvm]<br>enum [Status](-status/index.html)<br>This enum represents the possible states in which a Simulation could be. |

