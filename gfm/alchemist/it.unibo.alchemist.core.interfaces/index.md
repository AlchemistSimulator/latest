//[alchemist](../../index.md)/[it.unibo.alchemist.core.interfaces](index.md)

# Package it.unibo.alchemist.core.interfaces

[jvm]\
This package contains the interfaces to implement in order to create an engine.

## Types

| Name | Summary |
|---|---|
| [DependencyGraph](-dependency-graph/index.md) | [jvm]<br>interface [DependencyGraph](-dependency-graph/index.md)<[T](-dependency-graph/index.md)><br>This interface allows to separate the usage of a dependency graph from its implementation. |
| [Scheduler](-scheduler/index.md) | [jvm]<br>interface [Scheduler](-scheduler/index.md)<[T](-scheduler/index.md)><br>The type which describes the concentration of a molecule This interface is meant to be implemented by the data structure(s) which must manage the reactions. |
| [Simulation](-simulation/index.md) | [jvm]<br>interface [Simulation](-simulation/index.md)<[T](-simulation/index.md), [P](-simulation/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.model.interfaces/-layer/index.md)>?> : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html)<br>This interface forces simulations to be independent threads, and make them controllable from an external console. |
| [Status](-status/index.md) | [jvm]<br>enum [Status](-status/index.md)<br>This enum represents the possible states in which a Simulation could be. |
