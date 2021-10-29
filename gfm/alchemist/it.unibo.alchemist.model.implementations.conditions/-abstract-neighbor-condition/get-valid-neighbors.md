//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[AbstractNeighborCondition](index.md)/[getValidNeighbors](get-valid-neighbors.md)

# getValidNeighbors

[jvm]\
fun [getValidNeighbors](get-valid-neighbors.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../-abstract-condition/index.md)>, [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>

Searches in the given neighborhood which nodes satisfy the condition, and returns a list of valid neighbors. NOTE, it is NOT guaranteed that this method checks if the passed neighborhood is the actual neighborhood of the node. Make sure the passed neighborhood is up to date for avoid problems.

#### Return

a map of neighbors which satisfy the condition and their propensity
