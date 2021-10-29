//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPEREChemotaxis](index.md)/[SAPEREChemotaxis](-s-a-p-e-r-e-chemotaxis.md)

# SAPEREChemotaxis

[jvm]\
open fun [SAPEREChemotaxis](-s-a-p-e-r-e-chemotaxis.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), response: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), gradient: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), idPosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Builds a new SAPEREChemotaxis.

## Parameters

jvm

| | |
|---|---|
| environment | the environment |
| node | the node |
| response | the molecule to move |
| gradient | the molecule template that, once matched, will contain the node ID where move the molecule |
| idPosition | the argument number where to search for the node ID |
