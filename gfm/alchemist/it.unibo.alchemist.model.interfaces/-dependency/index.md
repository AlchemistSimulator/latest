//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Dependency](index.md)

# Dependency

[jvm]\
interface [Dependency](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This interface represents a token that may generate a dependency between two reactions. Some special built-in tokens are EVERYTHING, EVERY_MOLECULE, MOVEMENT, and NEIGHBORHOOD_CHANGE. Molecules are dependencies as well.

## Functions

| Name | Summary |
|---|---|
| [dependsOn](depends-on.md) | [jvm]<br>open fun [dependsOn](depends-on.md)(dependency: [Dependency](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether this dependency depends on the provided dependency. |
| [makesDependent](makes-dependent.md) | [jvm]<br>open fun [makesDependent](makes-dependent.md)(dependency: [Dependency](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether the provided dependency depends on this dependency. |

## Properties

| Name | Summary |
|---|---|
| [EVERY_MOLECULE](-e-v-e-r-y_-m-o-l-e-c-u-l-e.md) | [jvm]<br>val [EVERY_MOLECULE](-e-v-e-r-y_-m-o-l-e-c-u-l-e.md): [Dependency](index.md)<br>Declares a dependency towards any modified molecule in the reachable scope. |
| [EVERYTHING](-e-v-e-r-y-t-h-i-n-g.md) | [jvm]<br>val [EVERYTHING](-e-v-e-r-y-t-h-i-n-g.md): [Dependency](index.md)<br>Declares a dependency towards any other reaction in the reachable scope. |
| [MOVEMENT](-m-o-v-e-m-e-n-t.md) | [jvm]<br>val [MOVEMENT](-m-o-v-e-m-e-n-t.md): [Dependency](index.md)<br>Declares a dependency on movement of nodes in the reachable scope. |

## Inheritors

| Name |
|---|
| [Molecule](../-molecule/index.md) |
