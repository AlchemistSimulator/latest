---
title: cloneNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Node](index.html)/[cloneNode](clone-node.html)



# cloneNode



[jvm]\
abstract fun [cloneNode](clone-node.html)(currentTime: [Time](../-time/index.html)): [Node](index.html)<[T](index.html)>



Creates a new Node which is a clone of the current Node. The new Node will have all the current Node's properties, such as reactions and molecules, but it will also have a different ID.



#### Return



A new Node which is a clone of the current one.



## Parameters


jvm

| | |
|---|---|
| currentTime | the time at which the cloning operation happens |



#### Throws


| | |
|---|---|
| [java.lang.UnsupportedOperationException](https://docs.oracle.com/javase/8/docs/api/java/lang/UnsupportedOperationException.html) | if the implementation does not support node cloning. |



