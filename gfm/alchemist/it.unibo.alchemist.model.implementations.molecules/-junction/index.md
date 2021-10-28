//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.molecules](../index.md)/[Junction](index.md)

# Junction

[jvm]\
class [Junction](index.md) : [SimpleMolecule](../-simple-molecule/index.md)

Represents a junction between two cells.

## Constructors

| | |
|---|---|
| [Junction](-junction.md) | [jvm]<br>open fun [Junction](-junction.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), moleculesInCurrentNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, moleculesInNeighborNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Build a junction. |
| [Junction](-junction.md) | [jvm]<br>open fun [Junction](-junction.md)(toClone: [Junction](index.md))<br>Builds a junction from another junction. |

## Functions

| Name | Summary |
|---|---|
| [dependsOn](depends-on.md) | [jvm]<br>open fun [dependsOn](depends-on.md)(mol: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-simple-molecule/equals.md) | [jvm]<br>open fun [equals](../-simple-molecule/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](../-simple-molecule/get-name.md) | [jvm]<br>fun [getName](../-simple-molecule/get-name.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hashCode](../-simple-molecule/hash-code.md) | [jvm]<br>open fun [hashCode](../-simple-molecule/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.md)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reverse](reverse.md) | [jvm]<br>open fun [reverse](reverse.md)(): [Junction](index.md)<br>Return the reversed junction of the current junction. |
| [toString](../-simple-molecule/to-string.md) | [jvm]<br>open fun [toString](../-simple-molecule/to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [moleculesInCurrentNode](molecules-in-current-node.md) | [jvm]<br>private val [moleculesInCurrentNode](molecules-in-current-node.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [moleculesInNeighborNode](molecules-in-neighbor-node.md) | [jvm]<br>private val [moleculesInNeighborNode](molecules-in-neighbor-node.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.md), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
