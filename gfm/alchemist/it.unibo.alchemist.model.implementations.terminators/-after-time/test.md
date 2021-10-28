//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.terminators](../index.md)/[AfterTime](index.md)/[test](test.md)

# test

[jvm]\
open override fun [test](test.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Tries to access the simulation time from the [environment](test.md). If the simulation is unaccessible, throws an exception. Otherwise, reads the current time, and flips to true once it got past the provided [endTime](end-time.md).
