---
title: ReproduceGPSTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ReproduceGPSTrace](index.html)/[ReproduceGPSTrace](-reproduce-g-p-s-trace.html)



# ReproduceGPSTrace



[jvm]\
open fun [ReproduceGPSTrace](-reproduce-g-p-s-trace.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| path | resource(file, directory, ...) with GPS trace |
| cycle | true if the traces have to be distributed cyclically |
| normalizer | name of the class that implement the strategy to normalize the time |
| normalizerArgs | Args to build normalize |





[jvm]\
open fun [ReproduceGPSTrace](-reproduce-g-p-s-trace.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), cycle: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), normalizer: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), normalizerArgs: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction. Will be used to compute the distance to walk in every step, relying on [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)'s getRate() method. |
| speed | the average speed |
| path | resource(file, directory, ...) with GPS trace |
| cycle | true if the traces have to be distributed cyclically |
| normalizer | name of the class that implement the strategy to normalize the time |
| normalizerArgs | Args to build normalize |




