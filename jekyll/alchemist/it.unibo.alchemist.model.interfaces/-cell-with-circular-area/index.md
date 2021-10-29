---
title: CellWithCircularArea
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[CellWithCircularArea](index.html)



# CellWithCircularArea



[jvm]\
interface [CellWithCircularArea](index.html)<[P](index.html) : [Position](../-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [CellNode](../-cell-node/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> 

Implements a cell with a defined volume.



## Parameters


jvm

| | |
|---|---|
| <P> | [Position](../-position/index.html) type |



## Functions


| Name | Summary |
|---|---|
| [addJunction](../-cell-node/add-junction.html) | [jvm]<br>abstract fun [addJunction](../-cell-node/add-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), neighbor: [CellNode](../-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Add a junction to the current node. |
| [addPolarization](../-cell-node/add-polarization.html) | [jvm]<br>abstract fun [addPolarization](../-cell-node/add-polarization.html)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html))<br>add v to the polarization versor inside the cell; useful for considering the combination of various stimuli in a cell. |
| [addReaction](../-node/add-reaction.html) | [jvm]<br>abstract fun [addReaction](../-node/add-reaction.html)(p: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>) |
| [cloneNode](../-node/clone-node.html) | [jvm]<br>abstract fun [cloneNode](../-node/clone-node.html)(p: [Time](../-time/index.html)): [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-node/contains.html) | [jvm]<br>abstract fun [contains](../-node/contains.html)(p: [Molecule](../-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsJunction](../-cell-node/contains-junction.html) | [jvm]<br>abstract fun [containsJunction](../-cell-node/contains-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Return true if a junction is present in the current node, false otherwise. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAllNodesLinkWithJunction](../-cell-node/get-all-nodes-link-with-junction.html) | [jvm]<br>abstract fun [getAllNodesLinkWithJunction](../-cell-node/get-all-nodes-link-with-junction.html)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>A set of nodes which are linked by a junction with the current node |
| [getConcentration](../-node/get-concentration.html) | [jvm]<br>abstract fun [getConcentration](../-node/get-concentration.html)(p: [Molecule](../-molecule/index.html)): [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html) |
| [getContents](../-node/get-contents.html) | [jvm]<br>abstract fun [getContents](../-node/get-contents.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.html), [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [getDiameter](get-diameter.html) | [jvm]<br>abstract fun [getDiameter](get-diameter.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's diameter. |
| [getId](../-node/get-id.html) | [jvm]<br>abstract fun [getId](../-node/get-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJunctions](../-cell-node/get-junctions.html) | [jvm]<br>abstract fun [getJunctions](../-cell-node/get-junctions.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[CellNode](../-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>><br>the map junction - node - quantity |
| [getJunctionsCount](../-cell-node/get-junctions-count.html) | [jvm]<br>abstract fun [getJunctionsCount](../-cell-node/get-junctions-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The total number of junctions presents in this node |
| [getMoleculeCount](../-node/get-molecule-count.html) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNeighborsLinkWithJunction](../-cell-node/get-neighbors-link-with-junction.html) | [jvm]<br>abstract fun [getNeighborsLinkWithJunction](../-cell-node/get-neighbors-link-with-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Returns a set of ICellNode which are linked with the current node by a junction of the type j. |
| [getPolarizationVersor](../-cell-node/get-polarization-versor.html) | [jvm]<br>abstract fun [getPolarizationVersor](../-cell-node/get-polarization-versor.html)(): [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)<br>the [Position](../-position/index.html) representing the direction of cell polarization. |
| [getRadius](get-radius.html) | [jvm]<br>abstract fun [getRadius](get-radius.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's radius. |
| [getReactions](../-node/get-reactions.html) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>> |
| [hashCode](../-node/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |
| [removeConcentration](../-node/remove-concentration.html) | [jvm]<br>abstract fun [removeConcentration](../-node/remove-concentration.html)(p: [Molecule](../-molecule/index.html)) |
| [removeJunction](../-cell-node/remove-junction.html) | [jvm]<br>abstract fun [removeJunction](../-cell-node/remove-junction.html)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.html), neighbor: [CellNode](../-cell-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Remove a junction from this node. |
| [removeReaction](../-node/remove-reaction.html) | [jvm]<br>abstract fun [removeReaction](../-node/remove-reaction.html)(p: [Reaction](../-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)>) |
| [setConcentration](../-node/set-concentration.html) | [jvm]<br>abstract fun [setConcentration](../-node/set-concentration.html)(p: [Molecule](../-molecule/index.html), p1: [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)) |
| [setPolarization](../-cell-node/set-polarization.html) | [jvm]<br>abstract fun [setPolarization](../-cell-node/set-polarization.html)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html))<br>set the polarization versor, e.g. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.html)> |


## Inheritors


| Name |
|---|
| [CellNodeImpl](../../it.unibo.alchemist.model.implementations.nodes/-cell-node-impl/index.html) |
| [CircularDeformableCell](../-circular-deformable-cell/index.html) |

