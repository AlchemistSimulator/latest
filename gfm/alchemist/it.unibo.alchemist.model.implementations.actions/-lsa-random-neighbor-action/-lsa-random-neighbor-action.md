//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[LsaRandomNeighborAction](index.md)/[LsaRandomNeighborAction](-lsa-random-neighbor-action.md)

# LsaRandomNeighborAction

[jvm]\
open fun [LsaRandomNeighborAction](-lsa-random-neighbor-action.md)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), molecule: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGenerator: RandomGenerator)

Builds a new action in a neighborhood. es: +<id,X,n> This class extend LsaAbstractAction.

## Parameters

jvm

| | |
|---|---|
| environment | The environment to use |
| node | The source node |
| molecule | The IlsaMolecule instance you want to add to neighbor lsa space. |
| randomGenerator | the random engine |
