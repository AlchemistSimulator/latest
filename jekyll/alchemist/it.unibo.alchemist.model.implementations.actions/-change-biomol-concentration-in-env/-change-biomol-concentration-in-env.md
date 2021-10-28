---
title: ChangeBiomolConcentrationInEnv
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChangeBiomolConcentrationInEnv](index.html)/[ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html)



# ChangeBiomolConcentrationInEnv



[jvm]\
open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), deltaCon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGen: RandomGenerator)



Initialize a new [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) that change concentration of the given [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) of a "deltaCon" quantity.



## Parameters


jvm

| | |
|---|---|
| node | the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) where this action is located. |
| biomolecule | the [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) which concentration will be changed. |
| deltaCon | the quantity to add to actual concentration of [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) |
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) where the node is located. |
| randomGen | the random generator |





[jvm]\
open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGen: RandomGenerator)



Initialize a [ChangeBiomolConcentrationInEnv](index.html) with delta = -1.



## Parameters


jvm

| | |
|---|---|
| node | node the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) where this action is located. |
| biomolecule | the [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) which concentration will be changed. |
| environment | environment the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) where the node is located. |
| randomGen | the random generator |




