//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ChangeBiomolConcentrationInEnv](index.md)/[ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md)

# ChangeBiomolConcentrationInEnv

[jvm]\
open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), deltaCon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGen: RandomGenerator)

Initialize a new [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) that change concentration of the given [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) of a "deltaCon" quantity.

## Parameters

jvm

| | |
|---|---|
| node | the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) where this action is located. |
| biomolecule | the [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) which concentration will be changed. |
| deltaCon | the quantity to add to actual concentration of [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) |
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) where the node is located. |
| randomGen | the random generator |

[jvm]\
open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGen: RandomGenerator)

Initialize a [ChangeBiomolConcentrationInEnv](index.md) with delta = -1.

## Parameters

jvm

| | |
|---|---|
| node | node the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) where this action is located. |
| biomolecule | the [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) which concentration will be changed. |
| environment | environment the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) where the node is located. |
| randomGen | the random generator |
