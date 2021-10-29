---
title: initializationComplete
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)/[initializationComplete](initialization-complete.html)



# initializationComplete



[jvm]\
abstract fun [initializationComplete](initialization-complete.html)(atTime: [Time](../-time/index.html), environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.core.interfaces/-scheduler/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



This method is called when the environment has completed its initialization. Can be used by this reaction to compute its next execution time - in case such computation requires an inspection of the environment.



## Parameters


jvm

| | |
|---|---|
| atTime | the time at which the initialization of this reaction was accomplished |
| environment | the environment |




