//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[nodeAdded](node-added.md)

# nodeAdded

[jvm]\
abstract fun [nodeAdded](node-added.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)

This method must get called in case a node is added to the environment during the simulation and after its neighborhood has been computed (or can be consistently computed by the simulated environment). This method provides dependency computation and is responsible of correctly scheduling the Node's new reactions.

## Parameters

jvm

| | |
|---|---|
| node | the freshly added node |

#### Throws

| | |
|---|---|
| [java.lang.IllegalMonitorStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalMonitorStateException.html) | if the method gets called from a different thread than the simulation thread |
