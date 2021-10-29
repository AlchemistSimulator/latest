---
title: createDependencies
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[DependencyGraph](index.html)/[createDependencies](create-dependencies.html)



# createDependencies



[jvm]\
abstract fun [createDependencies](create-dependencies.html)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../-scheduler/index.html)>)



This method creates the dependencies when a new reaction is added to the environment. Please be careful when building the environment and populating the existing reactions map: this method assumes that all the dependencies among the existing reactions are correct and up to date.



## Parameters


jvm

| | |
|---|---|
| rh | the reaction handler whose dependencies should be calculated. |




