//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPEREMoveNodeAgent](index.md)/[SAPEREMoveNodeAgent](-s-a-p-e-r-e-move-node-agent.md)

# SAPEREMoveNodeAgent

[jvm]\
open fun [SAPEREMoveNodeAgent](-s-a-p-e-r-e-move-node-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md))

Creates a new SAPERE Local Agent stub. If you use this constructor, you must be sure that your agent does not modify any molecule (e.g. an agent that just moves a node).

## Parameters

jvm

| | |
|---|---|
| env | The current environment |
| node | The node in which this agent stays |

[jvm]\
open fun [SAPEREMoveNodeAgent](-s-a-p-e-r-e-move-node-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

Creates a new SAPERE Local Agent stub. Use this constructor if you agent modifies a molecule (locally!)

## Parameters

jvm

| | |
|---|---|
| env | The current environment |
| node | The node in which this agent stays |
| m | The modified molecule template |
