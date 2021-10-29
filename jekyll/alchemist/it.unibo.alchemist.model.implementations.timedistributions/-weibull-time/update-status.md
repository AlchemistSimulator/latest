---
title: updateStatus
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.timedistributions](../index.html)/[WeibullTime](index.html)/[updateStatus](update-status.html)



# updateStatus



[jvm]\
fun [updateStatus](update-status.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



Implement this method to update the distribution's internal status.



## Parameters


jvm

| | |
|---|---|
| currentTime | current time |
| executed | true if the reaction whose this distribution has been associated has just been executed |
| param | optional parameter passed by the reaction |
| environment | the current environment |




