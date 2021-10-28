//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPEREWalker](index.md)/[SAPEREWalker](-s-a-p-e-r-e-walker.md)

# SAPEREWalker

[jvm]\
open fun [SAPEREWalker](-s-a-p-e-r-e-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction (used to compute the movement length) |
| speed | the average speed of the node |
| interaction | the interaction factor |
| range | the interaction range |

[jvm]\
open fun [SAPEREWalker](-s-a-p-e-r-e-walker.md)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, tag: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| reaction | the reaction (used to compute the movement length) |
| tag | the molecule which identifies the interacting nodes |
| speed | the average speed of the node |
| interaction | the interaction factor |
| range | the interaction range |
