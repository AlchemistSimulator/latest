//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[CellNodeImpl](index.md)

# CellNodeImpl

[jvm]\
open class [CellNodeImpl](index.md)<[P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>?, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>?> : [DoubleNode](../-double-node/index.md), [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)> , [CellWithCircularArea](../../it.unibo.alchemist.model.interfaces/-cell-with-circular-area/index.md)<[P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>

## Parameters

jvm

| | |
|---|---|
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |

## Constructors

| | |
|---|---|
| [CellNodeImpl](-cell-node-impl.md) | [jvm]<br>open fun [CellNodeImpl](-cell-node-impl.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>, diameter: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>create a new cell node. |
| [CellNodeImpl](-cell-node-impl.md) | [jvm]<br>open fun [CellNodeImpl](-cell-node-impl.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md)>)<br>the environment |

## Functions

| Name | Summary |
|---|---|
| [addJunction](add-junction.md) | [jvm]<br>fun [addJunction](add-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), neighbor: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Add a junction to the current node. |
| [addPolarization](add-polarization.md) | [jvm]<br>fun [addPolarization](add-polarization.md)(v: [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md))<br>add v to the polarization versor inside the cell; useful for considering the combination of various stimuli in a cell. |
| [addReaction](../-abstract-node/add-reaction.md) | [jvm]<br>fun [addReaction](../-abstract-node/add-reaction.md)(reactionToAdd: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>) |
| [cloneNode](../-abstract-node/clone-node.md) | [jvm]<br>open fun [cloneNode](../-abstract-node/clone-node.md)(currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [AbstractNode](../-abstract-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)><br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces/-node/clone-node.md)(p: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)> |
| [compareTo](../-abstract-node/compare-to.md) | [jvm]<br>fun [compareTo](../-abstract-node/compare-to.md)(other: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](contains.md) | [jvm]<br>fun [contains](contains.md)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsJunction](contains-junction.md) | [jvm]<br>fun [containsJunction](contains-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Return true if a junction is present in the current node, false otherwise. |
| [equals](../-abstract-node/equals.md) | [jvm]<br>fun [equals](../-abstract-node/equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-abstract-node/for-each.md) | [jvm]<br>fun [forEach](../-abstract-node/for-each.md)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getAllNodesLinkWithJunction](get-all-nodes-link-with-junction.md) | [jvm]<br>fun [getAllNodesLinkWithJunction](get-all-nodes-link-with-junction.md)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>A set of nodes which are linked by a junction with the current node |
| [getConcentration](../-abstract-node/get-concentration.md) | [jvm]<br>open fun [getConcentration](../-abstract-node/get-concentration.md)(molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md) |
| [getContents](../-abstract-node/get-contents.md) | [jvm]<br>open fun [getContents](../-abstract-node/get-contents.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), [T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372) | [jvm]<br>fun [getId](../-homogeneous-physical-pedestrian2-d/index.md#2063123767%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJunctionsCount](get-junctions-count.md) | [jvm]<br>fun [getJunctionsCount](get-junctions-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The total number of junctions presents in this node |
| [getMoleculeCount](../-abstract-node/get-molecule-count.md) | [jvm]<br>open fun [getMoleculeCount](../-abstract-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNeighborsLinkWithJunction](get-neighbors-link-with-junction.md) | [jvm]<br>fun [getNeighborsLinkWithJunction](get-neighbors-link-with-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md)): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>><br>Returns a set of ICellNode which are linked with the current node by a junction of the type j. |
| [getRadius](get-radius.md) | [jvm]<br>fun [getRadius](get-radius.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the cell's radius. |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372) | [jvm]<br>fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.md#-301186114%2FFunctions%2F-267951372)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>> |
| [hashCode](../-abstract-node/hash-code.md) | [jvm]<br>fun [hashCode](../-abstract-node/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.md) | [jvm]<br>fun [iterator](../-abstract-node/iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)> |
| [removeConcentration](../-abstract-node/remove-concentration.md) | [jvm]<br>open fun [removeConcentration](../-abstract-node/remove-concentration.md)(moleculeToRemove: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [removeJunction](remove-junction.md) | [jvm]<br>fun [removeJunction](remove-junction.md)(j: [Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), neighbor: [CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>Remove a junction from this node. |
| [removeReaction](../-abstract-node/remove-reaction.md) | [jvm]<br>fun [removeReaction](../-abstract-node/remove-reaction.md)(reactionToRemove: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>) |
| [setConcentration](set-concentration.md) | [jvm]<br>fun [setConcentration](set-concentration.md)(mol: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), c: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)) |
| [setPolarization](set-polarization.md) | [jvm]<br>fun [setPolarization](set-polarization.md)(v: [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md))<br>set the polarization versor, e.g. |
| [spliterator](../-abstract-node/spliterator.md) | [jvm]<br>fun [spliterator](../-abstract-node/spliterator.md)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.conditions/-generic-molecule-present/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [diameter](diameter.md) | [jvm]<br>private open val [diameter](diameter.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [junctions](junctions.md) | [jvm]<br>private val [junctions](junctions.md): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[Junction](../../it.unibo.alchemist.model.implementations.molecules/-junction/index.md), [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[CellNode](../../it.unibo.alchemist.model.interfaces/-cell-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>> |
| [polarizationVersor](polarization-versor.md) | [jvm]<br>private open val [polarizationVersor](polarization-versor.md): [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.md) |

## Inheritors

| Name |
|---|
| [CircularDeformableCellImpl](../-circular-deformable-cell-impl/index.md) |
