---
title: cloneAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Action](index.html)/[cloneAction](clone-action.html)



# cloneAction



[jvm]\
abstract fun [cloneAction](clone-action.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>): [Action](index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>



This method allows to clone this action on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.



#### Return



the cloned action



## Parameters


jvm

| | |
|---|---|
| node | The node where to clone this [Action](index.html) |
| reaction | The reaction to which the CURRENT action is assigned |




