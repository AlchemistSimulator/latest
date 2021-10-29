---
title: update
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Reaction](index.html)/[update](update.html)



# update



[jvm]\
abstract fun [update](update.html)(currentTime: [Time](../-time/index.html), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../-environment/index.html)<[T](../-node/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



Updates the scheduling of this reaction.



## Parameters


jvm

| | |
|---|---|
| hasBeenExecuted | true if the reaction have just been executed. |
| currentTime | the current [Time](../-time/index.html) of execution. This is mandatory in order to correctly compute the time shift of an already-scheduled reaction |
| environment | the current environment |




