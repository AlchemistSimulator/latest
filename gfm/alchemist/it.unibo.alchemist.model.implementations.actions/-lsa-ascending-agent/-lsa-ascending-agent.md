//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[LsaAscendingAgent](index.md)/[LsaAscendingAgent](-lsa-ascending-agent.md)

# LsaAscendingAgent

[jvm]\
open fun [LsaAscendingAgent](-lsa-ascending-agent.md)(reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../../it.unibo.alchemist.model.implementations.linkingrules/-selective-adaptive-range/index.md)>, node: [ILsaNode](../../it.unibo.alchemist.model.interfaces/-i-lsa-node/index.md), molecule: [LsaMolecule](../../it.unibo.alchemist.model.implementations.molecules/-lsa-molecule/index.md), pos: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

## Parameters

jvm

| | |
|---|---|
| reaction | firing reaction |
| environment | the current environment |
| node | the current node |
| molecule | the LSA to inspect once moving (typically a gradient) |
| pos | the position in the LSA of the value to read for identifying the new position |
