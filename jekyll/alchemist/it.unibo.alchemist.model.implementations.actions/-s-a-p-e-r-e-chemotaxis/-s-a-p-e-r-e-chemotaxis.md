---
title: SAPEREChemotaxis
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPEREChemotaxis](index.html)/[SAPEREChemotaxis](-s-a-p-e-r-e-chemotaxis.html)



# SAPEREChemotaxis



[jvm]\
open fun [SAPEREChemotaxis](-s-a-p-e-r-e-chemotaxis.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, [P](../../it.unibo.alchemist.model/-s-a-p-e-r-e-incarnation/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), response: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), gradient: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), idPosition: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



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




