---
title: SimpleMolecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.molecules](../index.html)/[SimpleMolecule](index.html)



# SimpleMolecule



[jvm]\
open class [SimpleMolecule](index.html) : [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)

Simple implementation of Molecule.



## Constructors


| | |
|---|---|
| [SimpleMolecule](-simple-molecule.html) | [jvm]<br>open fun [SimpleMolecule](-simple-molecule.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()name: [CharSequence](https://docs.oracle.com/javase/8/docs/api/java/lang/CharSequence.html))<br>the molecule name |


## Functions


| Name | Summary |
|---|---|
| [dependsOn](../../it.unibo.alchemist.model.interfaces/-dependency/depends-on.html) | [jvm]<br>open fun [dependsOn](../../it.unibo.alchemist.model.interfaces/-dependency/depends-on.html)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](get-name.html) | [jvm]<br>fun [getName](get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Inheritors


| Name |
|---|
| [Junction](../-junction/index.html) |
| [Biomolecule](../-biomolecule/index.html) |
| [LsaMolecule](../-lsa-molecule/index.html) |

