//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[TimeDistribution](index.md)/[update](update.md)

# update

[jvm]\
abstract fun [update](update.md)(currentTime: [Time](../-time/index.md), executed: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), param: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), environment: [Environment](../-environment/index.md)<[T](../-node/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

Updates the internal status.

## Parameters

jvm

| | |
|---|---|
| currentTime | current time |
| executed | true if the reaction has just been executed |
| param | a parameter passed by the reaction |
| environment | the current environment |
