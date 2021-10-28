//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[PhysicalPedestrian](index.md)

# PhysicalPedestrian

[jvm]\
interface [PhysicalPedestrian](index.md)<[T](index.md), [P](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [Position](../-position/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> : [PhysicalNode](../-physical-node/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)> , [Pedestrian](../-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)> 

A pedestrian capable of interacting physically with others. [PhysicalPedestrian](index.md)s have a [comfortArea](comfort-area.md): when another node enters such area, this pedestrian is subject to a repulsion force. This is derived from [the work of Pelechano et al](https://bit.ly/3e3C7Tb). Note that [PhysicalPedestrian](index.md)s don't actively push each other, pushing behavior emerges from the interaction of pedestrians with different comfort areas (see the article linked above).

## Functions

| Name | Summary |
|---|---|
| [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1844535178%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1844535178%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-144457153%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneNode](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-144457153%2FFunctions%2F-267951372)(p0: [Time](../-time/index.md)): [Node](../-node/index.md)<[T](index.md)> |
| [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1076068299%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [compareTo](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1076068299%2FFunctions%2F-267951372)(other: [Node](../-node/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-905365364%2FFunctions%2F-267951372) | [jvm]<br>abstract operator fun [contains](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-905365364%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#2086990857%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#2086990857%2FFunctions%2F-267951372)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../-reaction/index.md)<[T](index.md)>>) |
| [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1182263796%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1182263796%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)): [T](index.md) |
| [getContents](../-node/get-contents.md) | [jvm]<br>abstract fun [getContents](../-node/get-contents.md)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../-molecule/index.md), [T](index.md)> |
| [getId](../-node/get-id.md) | [jvm]<br>abstract fun [getId](../-node/get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-node/get-molecule-count.md) | [jvm]<br>abstract fun [getMoleculeCount](../-node/get-molecule-count.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-node/get-reactions.md) | [jvm]<br>abstract fun [getReactions](../-node/get-reactions.md)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372) | [jvm]<br>abstract operator override fun [iterator](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#-1651023311%2FFunctions%2F-267951372)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |
| [physicalForces](physical-forces.md) | [jvm]<br>open override fun [physicalForces](physical-forces.md)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[P](index.md)> |
| [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1461493148%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md)) |
| [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeReaction](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#792936979%2FFunctions%2F-267951372)(p0: [Reaction](../-reaction/index.md)<[T](index.md)>) |
| [repulsionForce](repulsion-force.md) | [jvm]<br>abstract fun [repulsionForce](repulsion-force.md)(other: [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md)<[T](index.md), [P](index.md), *>): [P](index.md)<br>Computes the repulsion force caused by a node that entered the [comfortArea](comfort-area.md). |
| [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setConcentration](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.md#1246864287%2FFunctions%2F-267951372)(p0: [Molecule](../-molecule/index.md), p1: [T](index.md)) |
| [speed](../-pedestrian/speed.md) | [jvm]<br>abstract fun [speed](../-pedestrian/speed.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.loader.deployments/-close-to-g-p-s-trace/index.md#-1387152138%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../-reaction/index.md)<[T](index.md)>> |

## Properties

| Name | Summary |
|---|---|
| [comfortArea](comfort-area.md) | [jvm]<br>abstract val [comfortArea](comfort-area.md): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)><br>The comfort area of this pedestrian. |
| [membershipGroup](index.md#-1532258127%2FProperties%2F-267951372) | [jvm]<br>abstract val [membershipGroup](index.md#-1532258127%2FProperties%2F-267951372): [PedestrianGroup](../-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)> |
| [shape](index.md#314474649%2FProperties%2F-267951372) | [jvm]<br>abstract val [shape](index.md#314474649%2FProperties%2F-267951372): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.md)<[P](index.md), [A](index.md)> |

## Inheritors

| Name |
|---|
| [PhysicalPedestrian2D](../-physical-pedestrian2-d/index.md) |
