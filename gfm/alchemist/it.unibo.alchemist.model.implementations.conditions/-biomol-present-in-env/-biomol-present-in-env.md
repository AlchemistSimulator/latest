//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[BiomolPresentInEnv](index.md)/[BiomolPresentInEnv](-biomol-present-in-env.md)

# BiomolPresentInEnv

[jvm]\
open fun [BiomolPresentInEnv](-biomol-present-in-env.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), concentration: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))

Initialize condition for extra-cellular environment, implemented as a set of [EnvironmentNode](../../it.unibo.alchemist.model.interfaces/-environment-node/index.md).

## Parameters

jvm

| | |
|---|---|
| biomolecule | the [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) which the condition is about. |
| concentration | the requested concentration. |
| node | the node where this condition is located; |
| env | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) where the node is located. |
