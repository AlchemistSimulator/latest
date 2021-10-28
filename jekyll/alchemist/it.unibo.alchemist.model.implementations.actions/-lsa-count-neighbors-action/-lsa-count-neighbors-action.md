---
title: LsaCountNeighborsAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[LsaCountNeighborsAction](index.html)/[LsaCountNeighborsAction](-lsa-count-neighbors-action.html)



# LsaCountNeighborsAction



[jvm]\
open fun [LsaCountNeighborsAction](-lsa-count-neighbors-action.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), molToCount: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), countVar: HashString, rand: RandomGenerator)

open fun [LsaCountNeighborsAction](-lsa-count-neighbors-action.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), molToCount: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html), countVar: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), rand: RandomGenerator)



Builds a new action that counts neighbors which contain in their lsaSpace an lsaMolecule matching mol. The effect of this Action is to add to the matches list the variable countVar. The execution has no effect on the set of influenced molecules for the reaction.



## Parameters


jvm

| | |
|---|---|
| environment | The environment to use |
| node | The source node |
| molToCount | The IlsaMolecule instance you want to search in neighbor lsa space. |
| countVar | The String representing the name of the counting var. (to add to matches map) |
| rand | Random engine |




