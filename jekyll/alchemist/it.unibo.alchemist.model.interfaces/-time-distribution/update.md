---
title: update
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[TimeDistribution](index.html)/[update](update.html)



# update



[jvm]\
abstract fun [update](update.html)(currentTime: [Time](../-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



Updates the internal status.



## Parameters


jvm

| | |
|---|---|
| currentTime | current time |
| executed | true if the reaction has just been executed |
| param | a parameter passed by the reaction |
| environment | the current environment |




