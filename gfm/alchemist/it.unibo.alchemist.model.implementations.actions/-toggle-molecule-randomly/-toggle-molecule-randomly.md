//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ToggleMoleculeRandomly](index.md)/[ToggleMoleculeRandomly](-toggle-molecule-randomly.md)

# ToggleMoleculeRandomly

[jvm]\
fun <[T](index.md)> [ToggleMoleculeRandomly](-toggle-molecule-randomly.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](index.md), odds: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
|  | <T> concentration type |
| node | the node containing the molecule to toggle |
| randomGenerator | random number generator to use |
| molecule | the molecule to toggle |
| concentration | the concentration to use for the "on" state |
| odds | probability to toggle the molecule every time the action is triggered |
