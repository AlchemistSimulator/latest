---
title: SAPEREMoveLSAToAgent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[SAPEREMoveLSAToAgent](index.html)/[SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html)



# SAPEREMoveLSAToAgent



[jvm]\
open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), destId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))



This is the constructor that should be called from DSL. Dynamically computes the destination node if an id is given.



## Parameters


jvm

| | |
|---|---|
| env | the current environment |
| node | the source node, where this action is programmed |
| destId | the destination node id |
| template | the template LSA to match and move |





[jvm]\
open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.html)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), dest: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.html), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html))



## Parameters


jvm

| | |
|---|---|
| node | the source node, where this action is programmed |
| dest | the destination node, where this action will move the matched intance |
| template | the template LSA to match and move |




