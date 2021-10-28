---
title: Junction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.molecules](../index.html)/[Junction](index.html)



# Junction



[jvm]\
class [Junction](index.html) : [SimpleMolecule](../-simple-molecule/index.html)

Represents a junction between two cells.



## Constructors


| | |
|---|---|
| [Junction](-junction.html) | [jvm]<br>open fun [Junction](-junction.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), moleculesInCurrentNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.html), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, moleculesInNeighborNode: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.html), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>)<br>Build a junction. |
| [Junction](-junction.html) | [jvm]<br>open fun [Junction](-junction.html)(toClone: [Junction](index.html))<br>Builds a junction from another junction. |


## Functions


| Name | Summary |
|---|---|
| [dependsOn](depends-on.html) | [jvm]<br>open fun [dependsOn](depends-on.html)(mol: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-simple-molecule/equals.html) | [jvm]<br>open fun [equals](../-simple-molecule/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getName](../-simple-molecule/get-name.html) | [jvm]<br>fun [getName](../-simple-molecule/get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [hashCode](../-simple-molecule/hash-code.html) | [jvm]<br>open fun [hashCode](../-simple-molecule/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html) | [jvm]<br>open fun [makesDependent](../../it.unibo.alchemist.model.interfaces/-dependency/makes-dependent.html)(dependency: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reverse](reverse.html) | [jvm]<br>open fun [reverse](reverse.html)(): [Junction](index.html)<br>Return the reversed junction of the current junction. |
| [toString](../-simple-molecule/to-string.html) | [jvm]<br>open fun [toString](../-simple-molecule/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [moleculesInCurrentNode](molecules-in-current-node.html) | [jvm]<br>private val [moleculesInCurrentNode](molecules-in-current-node.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.html), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [moleculesInNeighborNode](molecules-in-neighbor-node.html) | [jvm]<br>private val [moleculesInNeighborNode](molecules-in-neighbor-node.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Biomolecule](../-biomolecule/index.html), [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |

