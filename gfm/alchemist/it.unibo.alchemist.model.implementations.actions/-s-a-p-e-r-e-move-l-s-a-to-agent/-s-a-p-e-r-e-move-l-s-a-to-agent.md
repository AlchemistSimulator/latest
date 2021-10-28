//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPEREMoveLSAToAgent](index.md)/[SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.md)

# SAPEREMoveLSAToAgent

[jvm]\
open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), destId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

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
open fun [SAPEREMoveLSAToAgent](-s-a-p-e-r-e-move-l-s-a-to-agent.md)(node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), dest: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), template: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

## Parameters

jvm

| | |
|---|---|
| node | the source node, where this action is programmed |
| dest | the destination node, where this action will move the matched intance |
| template | the template LSA to match and move |
