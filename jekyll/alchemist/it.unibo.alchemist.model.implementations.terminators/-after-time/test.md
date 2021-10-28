---
title: test
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.terminators](../index.html)/[AfterTime](index.html)/[test](test.html)



# test



[jvm]\
open override fun [test](test.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, *>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Tries to access the simulation time from the [environment](test.html). If the simulation is unaccessible, throws an exception. Otherwise, reads the current time, and flips to true once it got past the provided [endTime](end-time.html).




