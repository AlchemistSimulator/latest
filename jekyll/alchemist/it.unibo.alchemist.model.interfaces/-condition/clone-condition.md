---
title: cloneCondition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Condition](index.html)/[cloneCondition](clone-condition.html)



# cloneCondition



[jvm]\
abstract fun [cloneCondition](clone-condition.html)(node: [Node](../-node/index.html)<[T](../-node/index.html)>, reaction: [Reaction](../-reaction/index.html)<[T](../-node/index.html)>): [Condition](index.html)<[T](../-node/index.html)>



This method allows to clone this action on a new node. It may result useful to support runtime creation of nodes with the same reaction programming, e.g. for morphogenesis.



#### Return



the cloned action



## Parameters


jvm

| | |
|---|---|
| node | The node where to clone this [Condition](index.html) |
| reaction | The [Reaction](../-reaction/index.html) where to clone this [Condition](index.html) |




