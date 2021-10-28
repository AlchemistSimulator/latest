//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[SimpleMolecule](index.md)

# SimpleMolecule

[jvm]\
open class [SimpleMolecule](index.md) : [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)

Simple implementation of Molecule.

## Constructors

| | |
|---|---|
| [SimpleMolecule](-simple-molecule.md) | [jvm]<br>open fun [SimpleMolecule](-simple-molecule.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()name: [CharSequence](https://docs.oracle.com/javase/8/docs/api/java/lang/CharSequence.html))<br>the molecule name |

## Functions

| Name | Summary |
|---|---|
| [dependsOn](../../it.unibo.alchemist.model.interfaces/-dependency/depends-on.md) | [jvm]<br>open fun [dependsOn](../../it.unibo.alchemist.model.interfaces/-dependency/depends-on.md)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](get-name.md) | [jvm]<br>fun [getName](get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Inheritors

| Name |
|---|
| [Junction](../-junction/index.md) |
| [Biomolecule](../-biomolecule/index.md) |
| [LsaMolecule](../-lsa-molecule/index.md) |
