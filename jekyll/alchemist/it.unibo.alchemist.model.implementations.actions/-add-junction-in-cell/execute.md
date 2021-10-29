---
title: execute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AddJunctionInCell](index.html)/[execute](execute.html)



# execute



[jvm]\
open fun [execute](execute.html)()



If no target node is given DO NOTHING. The junction can not be created.



#### Throws


| | |
|---|---|
| [java.lang.UnsupportedOperationException](https://docs.oracle.com/javase/8/docs/api/java/lang/UnsupportedOperationException.html) | if this method is called. |




[jvm]\
open fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)



Create the junction that links the node where this action is executed and the target node.




