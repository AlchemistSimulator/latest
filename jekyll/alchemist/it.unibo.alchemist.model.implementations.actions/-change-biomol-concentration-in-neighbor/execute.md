---
title: execute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChangeBiomolConcentrationInNeighbor](index.html)/[execute](execute.html)



# execute



[jvm]\
open fun [execute](execute.html)()



Execute the action on a random neighbor if the node has a neighborhood. Otherwise do nothing.





[jvm]\
open fun [execute](execute.html)(targetNode: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)



Execute the action on the given target node. NOTE, it is NOT guaranteed that this method checks if the target node is in the actual neighborhood of the node.



## Parameters


jvm

| | |
|---|---|
| targetNode | the node where the action will be execute |



