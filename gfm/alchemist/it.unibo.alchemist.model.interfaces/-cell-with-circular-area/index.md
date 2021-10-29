//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[CellWithCircularArea](index.md)

# CellWithCircularArea

[jvm]\
interface [CellWithCircularArea](index.md)<[P](index.md) : [Position](../-position/index.md)<out [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>?> : [CellNode](../-cell-node/index.md)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> 

Implements a cell with a defined volume.

## Parameters

jvm

| | |
|---|---|
| <P> | [Position](../-position/index.md) type |

## Functions

| Name | Summary |
|---|---|
| [addJunction](../-cell-node/add-junction.md) | [jvm]<br>abstract fun [addJunction](../-cell-node/add-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), neighbor: [CellNode](../-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Add a junction to the current node. |
| [addPolarization](../-cell-node/add-polarization.md) | [jvm]<br>abstract fun [addPolarization](../-cell-node/add-polarization.md)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md))<br>add v to the polarization versor inside the cell; useful for considering the combination of various stimuli in a cell. |
| [addReaction](../-node/add-reaction.md) | [jvm]<br>abstract fun [addReaction](../-node/add-reaction.md)(p: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>) |
| [cloneNode](../-node/clone-node.md) | [jvm]<br>abstract fun [cloneNode](../-node/clone-node.md)(p: [Time](../-time/index.md)): [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |
| [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](../-g-p-s-point/index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-node/contains.md) | [jvm]<br>abstract fun [contains](../-node/contains.md)(p: [Molecule](../-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsJunction](../-cell-node/contains-junction.md) | [jvm]<br>abstract fun [containsJunction](../-cell-node/contains-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Return true if a junction is present in the current node, false otherwise. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAllNodesLinkWithJunction](../-cell-node/get-all-nodes-link-with-junction.md) | [jvm]<br>abstract fun [getAllNodesLinkWithJunction](../-cell-node/get-all-nodes-link-with-junction.md)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>A set of nodes which are linked by a junction with the current node |
| [getConcentration](../-node/get-concentration.md) | [jvm]<br>abstract fun [getConcentration](../-node/get-concentration.md)(p: [Molecule](../-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md) |
| [getContents](../-node/get-contents.md) | [jvm]<br>abstract fun [getContents](../-node/get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |
| [getDiameter](get-diameter.md) | [jvm]<br>abstract fun [getDiameter](get-diameter.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's diameter. |
| [getId](../-node/get-id.md) | [jvm]<br>abstract fun [getId](../-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJunctions](../-cell-node/get-junctions.md) | [jvm]<br>abstract fun [getJunctions](../-cell-node/get-junctions.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[CellNode](../-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>><br>the map junction - node - quantity |
| [getJunctionsCount](../-cell-node/get-junctions-count.md) | [jvm]<br>abstract fun [getJunctionsCount](../-cell-node/get-junctions-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The total number of junctions presents in this node |
| [getMoleculeCount](../-node/get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNeighborsLinkWithJunction](../-cell-node/get-neighbors-link-with-junction.md) | [jvm]<br>abstract fun [getNeighborsLinkWithJunction](../-cell-node/get-neighbors-link-with-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Returns a set of ICellNode which are linked with the current node by a junction of the type j. |
| [getPolarizationVersor](../-cell-node/get-polarization-versor.md) | [jvm]<br>abstract fun [getPolarizationVersor](../-cell-node/get-polarization-versor.md)(): [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)<br>the [Position](../-position/index.md) representing the direction of cell polarization. |
| [getRadius](get-radius.md) | [jvm]<br>abstract fun [getRadius](get-radius.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's radius. |
| [getReactions](../-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>> |
| [hashCode](../-node/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |
| [removeConcentration](../-node/remove-concentration.md) | [jvm]<br>abstract fun [removeConcentration](../-node/remove-concentration.md)(p: [Molecule](../-molecule/index.md)) |
| [removeJunction](../-cell-node/remove-junction.md) | [jvm]<br>abstract fun [removeJunction](../-cell-node/remove-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), neighbor: [CellNode](../-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Remove a junction from this node. |
| [removeReaction](../-node/remove-reaction.md) | [jvm]<br>abstract fun [removeReaction](../-node/remove-reaction.md)(p: [Reaction](../-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)>) |
| [setConcentration](../-node/set-concentration.md) | [jvm]<br>abstract fun [setConcentration](../-node/set-concentration.md)(p: [Molecule](../-molecule/index.md), p1: [T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)) |
| [setPolarization](../-cell-node/set-polarization.md) | [jvm]<br>abstract fun [setPolarization](../-cell-node/set-polarization.md)(v: [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md))<br>set the polarization versor, e.g. |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.nodes/-abstract-node/index.md)> |

## Inheritors

| Name |
|---|
| [CellNodeImpl](../../it.unibo.alchemist.model.implementations.nodes/-cell-node-impl/index.md) |
| [CircularDeformableCell](../-circular-deformable-cell/index.md) |
