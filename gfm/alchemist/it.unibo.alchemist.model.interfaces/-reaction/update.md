//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Reaction](index.md)/[update](update.md)

# update

[jvm]\
abstract fun [update](update.md)(currentTime: [Time](../-time/index.md), hasBeenExecuted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), environment: [Environment](../-environment/index.md)<[T](../-action/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

Updates the scheduling of this reaction.

## Parameters

jvm

| | |
|---|---|
| hasBeenExecuted | true if the reaction have just been executed. |
| currentTime | the current [Time](../-time/index.md) of execution. This is mandatory in order to correctly compute the time shift of an already-scheduled reaction |
| environment | the current environment |
