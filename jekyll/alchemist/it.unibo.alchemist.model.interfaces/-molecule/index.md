---
title: Molecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Molecule](index.html)



# Molecule



[jvm]\
interface [Molecule](index.html) : [Dependency](../-dependency/index.html)

Interface for a molecule.



## Functions


| Name | Summary |
|---|---|
| [dependsOn](../-dependency/depends-on.html) | [jvm]<br>open fun [dependsOn](../-dependency/depends-on.html)(dependency: [Dependency](../-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether this dependency depends on the provided dependency. |
| [getName](get-name.html) | [jvm]<br>abstract fun [getName](get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>the name of this [Molecule](index.html) |
| [makesDependent](../-dependency/makes-dependent.html) | [jvm]<br>open fun [makesDependent](../-dependency/makes-dependent.html)(dependency: [Dependency](../-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determines whether the provided dependency depends on this dependency. |


## Inheritors


| Name |
|---|
| [SimpleMolecule](../../it.unibo.alchemist.model.implementations.molecules/-simple-molecule/index.html) |
| [ILsaMolecule](../-i-lsa-molecule/index.html) |

