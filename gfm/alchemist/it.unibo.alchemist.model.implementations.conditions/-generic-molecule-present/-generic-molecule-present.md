//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.conditions](../index.md)/[GenericMoleculePresent](index.md)/[GenericMoleculePresent](-generic-molecule-present.md)

# GenericMoleculePresent

[jvm]\
open fun [GenericMoleculePresent](-generic-molecule-present.md)(n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>, mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), quantity: [T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md))

Builds a new condition, which checks if the molecule exists or not inside the node n.

## Parameters

jvm

| | |
|---|---|
| mol | the molecule whose presence should be checked |
| n | the current node |
| quantity | the amount of molecules which should be present. Must be positive. |
