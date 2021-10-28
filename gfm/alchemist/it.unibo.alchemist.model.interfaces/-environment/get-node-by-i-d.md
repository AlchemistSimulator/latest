//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)/[getNodeByID](get-node-by-i-d.md)

# getNodeByID

[jvm]\
abstract fun [getNodeByID](get-node-by-i-d.md)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>

Allows to access a node known its id. Depending on the implementation, this method may or not be optimized (namely, id could run in constant or linear time with the number of nodes).

#### Return

the node with that id, or null if it does not exist in this environment

## Parameters

jvm

| | |
|---|---|
| id | the node's ID |
