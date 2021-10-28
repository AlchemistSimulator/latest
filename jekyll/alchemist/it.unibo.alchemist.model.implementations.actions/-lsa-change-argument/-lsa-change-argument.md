---
title: LsaChangeArgument
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[LsaChangeArgument](index.html)/[LsaChangeArgument](-lsa-change-argument.html)



# LsaChangeArgument



[jvm]\
open fun [LsaChangeArgument](-lsa-change-argument.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), listTarget: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>, targetVariable: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), random: RandomGenerator)



Builds a new action that test neighbors which contain in their lsaSpace an lsaMolecule matching {target,Type}. The effect of this Action is to add to the matches map the variable PreferredType (the most present type in neighborhood). The execution has no effect on influenced molecule of reaction.



## Parameters


jvm

| | |
|---|---|
| environment | The environment to use |
| node | The source node |
| listTarget | Gradients list |
| targetVariable | Variable name |
| random | Random engine |



