---
title: CellNodeImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[CellNodeImpl](index.html)



# CellNodeImpl



[jvm]\
open class [CellNodeImpl](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [DoubleNode](../-double-node/index.html), [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> , [CellWithCircularArea](../../it.unibo.alchemist.model.interfaces/-cell-with-circular-area/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Constructors


| | |
|---|---|
| [CellNodeImpl](-cell-node-impl.html) | [jvm]<br>open fun [CellNodeImpl](-cell-node-impl.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, diameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>create a new cell node. |
| [CellNodeImpl](-cell-node-impl.html) | [jvm]<br>open fun [CellNodeImpl](-cell-node-impl.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>)<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [addJunction](add-junction.html) | [jvm]<br>fun [addJunction](add-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), neighbor: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Add a junction to the current node. |
| [addPolarization](add-polarization.html) | [jvm]<br>fun [addPolarization](add-polarization.html)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html))<br>add v to the polarization versor inside the cell; useful for considering the combination of various stimuli in a cell. |
| [addReaction](../-abstract-node/add-reaction.html) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.html)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>) |
| [cloneNode](../-abstract-node/clone-node.html) | [jvm]<br>open fun [cloneNode](../-abstract-node/clone-node.html)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.html)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [compareTo](../-abstract-node/compare-to.html) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.html)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.html) | [jvm]<br>fun [contains](contains.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsJunction](contains-junction.html) | [jvm]<br>fun [containsJunction](contains-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Return true if a junction is present in the current node, false otherwise. |
| [equals](../-abstract-node/equals.html) | [jvm]<br>fun [equals](../-abstract-node/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.html) | [jvm]<br>fun [forEach](../-abstract-node/for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAllNodesLinkWithJunction](get-all-nodes-link-with-junction.html) | [jvm]<br>fun [getAllNodesLinkWithJunction](get-all-nodes-link-with-junction.html)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>A set of nodes which are linked by a junction with the current node |
| [getConcentration](../-abstract-node/get-concentration.html) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.html)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJunctionsCount](get-junctions-count.html) | [jvm]<br>fun [getJunctionsCount](get-junctions-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The total number of junctions presents in this node |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNeighborsLinkWithJunction](get-neighbors-link-with-junction.html) | [jvm]<br>fun [getNeighborsLinkWithJunction](get-neighbors-link-with-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Returns a set of ICellNode which are linked with the current node by a junction of the type j. |
| [getRadius](get-radius.html) | [jvm]<br>fun [getRadius](get-radius.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's radius. |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>fun [iterator](../-abstract-node/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [removeConcentration](../-abstract-node/remove-concentration.html) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.html)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeJunction](remove-junction.html) | [jvm]<br>fun [removeJunction](remove-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), neighbor: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Remove a junction from this node. |
| [removeReaction](../-abstract-node/remove-reaction.html) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.html)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>) |
| [setConcentration](set-concentration.html) | [jvm]<br>fun [setConcentration](set-concentration.html)(mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), c: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)) |
| [setPolarization](set-polarization.html) | [jvm]<br>fun [setPolarization](set-polarization.html)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html))<br>set the polarization versor, e.g. |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [diameter](diameter.html) | [jvm]<br>private open val [diameter](diameter.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [junctions](junctions.html) | [jvm]<br>private val [junctions](junctions.html): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>> |
| [polarizationVersor](polarization-versor.html) | [jvm]<br>private open val [polarizationVersor](polarization-versor.html): [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html) |


## Inheritors


| Name |
|---|
| [CircularDeformableCellImpl](../-circular-deformable-cell-impl/index.html) |

