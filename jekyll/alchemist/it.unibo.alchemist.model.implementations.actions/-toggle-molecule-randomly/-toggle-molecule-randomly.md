---
title: ToggleMoleculeRandomly
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ToggleMoleculeRandomly](index.html)/[ToggleMoleculeRandomly](-toggle-molecule-randomly.html)



# ToggleMoleculeRandomly



[jvm]\
fun <[T](index.html)> [ToggleMoleculeRandomly](-toggle-molecule-randomly.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, randomGenerator: RandomGenerator, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), concentration: [T](index.html), odds: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



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




