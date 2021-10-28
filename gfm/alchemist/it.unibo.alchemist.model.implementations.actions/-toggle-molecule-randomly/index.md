//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ToggleMoleculeRandomly](index.md)

# ToggleMoleculeRandomly

[jvm]\
open class [ToggleMoleculeRandomly](index.md)<[T](index.md)>(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **randomGenerator**: RandomGenerator, **molecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), **concentration**: [T](index.md), **odds**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [ToggleMolecule](../-toggle-molecule/index.md)<[T](index.md)> 

Treats molecule as a probabilistic switch:

<ul><li>if it is present, then with probability odds it's removed from node;</li><li>otherwise, with probability odds it is inserted in node with the provided concentration.</li></ul>

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

## Constructors

| | |
|---|---|
| [ToggleMoleculeRandomly](-toggle-molecule-randomly.md) | [jvm]<br>fun <[T](index.md)> [ToggleMoleculeRandomly](-toggle-molecule-randomly.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](index.md), odds: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br><T> concentration type |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open override fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [ToggleMoleculeRandomly](index.md)<[T](index.md)> |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(m: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](execute.md) | [jvm]<br>open override fun [execute](execute.md)()<br>Rolls the dice and toggles the molecule. |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-toggle-molecule/get-context.md) | [jvm]<br>open override fun [getContext](../-toggle-molecule/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](index.md#-330064727%2FFunctions%2F-267951372)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), concentration: [T](index.md)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |