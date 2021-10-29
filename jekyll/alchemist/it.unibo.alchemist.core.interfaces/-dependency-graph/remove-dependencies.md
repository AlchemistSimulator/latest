---
title: removeDependencies
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[DependencyGraph](index.html)/[removeDependencies](remove-dependencies.html)



# removeDependencies



[jvm]\
abstract fun [removeDependencies](remove-dependencies.html)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-scheduler/index.html)>)



This method removes all the dependencies (both in and out dependencies) for a given reaction handler. This method is meant to be used in order to keep the dependencies clean when removing a reaction.



## Parameters


jvm

| | |
|---|---|
| rh | the reaction handler whose dependencies will be deleted. |




