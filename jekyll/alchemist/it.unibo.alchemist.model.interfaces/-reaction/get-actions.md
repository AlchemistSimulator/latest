---
title: getActions
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)/[getActions](get-actions.html)



# getActions



[jvm]\
abstract fun [getActions](get-actions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Action](../-action/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html)>>



#### Return



The list of [Action](../-action/index.html)s of the [Reaction](index.html). There is no specification if the list will be a copy of the internal list or a reference. It will depend on implementations. Please be careful when you modify this list.




