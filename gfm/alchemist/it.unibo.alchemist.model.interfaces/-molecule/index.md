//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Molecule](index.md)

# Molecule

[jvm]\
interface [Molecule](index.md) : [Dependency](../-dependency/index.md)

Interface for a molecule.

## Functions

| Name | Summary |
|---|---|
| [dependsOn](../-dependency/depends-on.md) | [jvm]<br>open fun [dependsOn](../-dependency/depends-on.md)(dependency: [Dependency](../-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether this dependency depends on the provided dependency. |
| [getName](get-name.md) | [jvm]<br>abstract fun [getName](get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the name of this [Molecule](index.md) |
| [makesDependent](../-dependency/makes-dependent.md) | [jvm]<br>open fun [makesDependent](../-dependency/makes-dependent.md)(dependency: [Dependency](../-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether the provided dependency depends on this dependency. |

## Inheritors

| Name |
|---|
| [SimpleMolecule](../../it.unibo.alchemist.model.implementations.molecules/-simple-molecule/index.md) |
| [ILsaMolecule](../-i-lsa-molecule/index.md) |
