---
title: cloneOnNewNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)/[cloneOnNewNode](clone-on-new-node.html)



# cloneOnNewNode



[jvm]\
abstract fun [cloneOnNewNode](clone-on-new-node.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>, currentTime: [Time](../-time/index.html)): [Reaction](index.html)<[T](../-node/index.html)>



This method allows to clone this reaction on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.



#### Return



the cloned action



## Parameters


jvm

| | |
|---|---|
| node | The node where to clone this Reaction |
| currentTime | the time at which the clone is created (required to correctly clone the [TimeDistribution](../-time-distribution/index.html)s) |




