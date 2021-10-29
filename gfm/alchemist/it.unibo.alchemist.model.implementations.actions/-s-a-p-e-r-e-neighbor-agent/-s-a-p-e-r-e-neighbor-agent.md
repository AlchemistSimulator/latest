//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SAPERENeighborAgent](index.md)/[SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)

# SAPERENeighborAgent

[jvm]\
open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

Creates a new SAPERE Neighbor Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1.

## Parameters

jvm

| | |
|---|---|
| env | The current environment |
| node | The node in which this agent stays |
| m1 | The molecule template it modifies |

[jvm]\
open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

Creates a new SAPERE Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1 and/or the template passed in m2.

## Parameters

jvm

| | |
|---|---|
| env | The current environment |
| node | The node in which this agent stays |
| m1 | The first molecule template it modifies |
| m2 | The second molecule template it modifies |

[jvm]\
open fun [SAPERENeighborAgent](-s-a-p-e-r-e-neighbor-agent.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), m1: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m2: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md), m3: [ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md))

Creates a new SAPERE Agent stub. If you use this constructor, you must be sure that your agent only modifies molecules matching the template passed as m1 and/or the template passed in m2 and/or the template passed in m3.

## Parameters

jvm

| | |
|---|---|
| env | The current environment |
| node | The node in which this agent stays |
| m1 | The first molecule template it modifies |
| m2 | The second molecule template it modifies |
| m3 | The third molecule template it modifies |
