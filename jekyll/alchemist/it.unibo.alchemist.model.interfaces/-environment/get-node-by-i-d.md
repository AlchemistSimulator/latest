---
title: getNodeByID
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Environment](index.html)/[getNodeByID](get-node-by-i-d.html)



# getNodeByID



[jvm]\
abstract fun [getNodeByID](get-node-by-i-d.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.html)<[T](../-node/index.html)>



Allows to access a node known its id. Depending on the implementation, this method may or not be optimized (namely, id could run in constant or linear time with the number of nodes).



#### Return



the node with that id, or null if it does not exist in this environment



## Parameters


jvm

| | |
|---|---|
| id | the node's ID |




