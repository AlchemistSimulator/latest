//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Reaction](index.md)/[initializationComplete](initialization-complete.md)

# initializationComplete

[jvm]\
abstract fun [initializationComplete](initialization-complete.md)(atTime: [Time](../-time/index.md), environment: [Environment](../-environment/index.md)<[T](../-action/index.md), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)

This method is called when the environment has completed its initialization. Can be used by this reaction to compute its next execution time - in case such computation requires an inspection of the environment.

## Parameters

jvm

| | |
|---|---|
| atTime | the time at which the initialization of this reaction was accomplished |
| environment | the environment |
