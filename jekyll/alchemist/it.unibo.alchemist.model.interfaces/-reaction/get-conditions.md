---
title: getConditions
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)/[getConditions](get-conditions.html)



# getConditions



[jvm]\
abstract fun [getConditions](get-conditions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>



#### Return



The list of [Condition](../-condition/index.html)s of the [Reaction](index.html). There is no specification if the list will be a copy of the internal list or a reference. It will depend on implementations. Please be careful when you modify this list.




