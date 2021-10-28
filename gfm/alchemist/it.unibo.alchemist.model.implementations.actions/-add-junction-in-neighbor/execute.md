//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AddJunctionInNeighbor](index.md)/[execute](execute.md)

# execute

[jvm]\
open fun [execute](execute.md)()

If no target node is given DO NOTHING. The junction can not be created.

#### Throws

| | |
|---|---|
| [java.lang.UnsupportedOperationException](https://docs.oracle.com/javase/8/docs/api/java/lang/UnsupportedOperationException.html) | if this method is called. |

[jvm]\
open fun [execute](execute.md)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)

Create the junction that links the target node and the node when this action is executed.
