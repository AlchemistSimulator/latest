---
title: CircleNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[CircleNode](index.html)



# CircleNode



[jvm]\
open class [CircleNode](index.html)<[T](index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [AbstractNode](../-abstract-node/index.html)<[T](index.html)> , [NodeWithShape](../../it.unibo.alchemist.model.interfaces.nodes/-node-with-shape/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)> 

A [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) with a circle shape meant to be added to a [it.unibo.alchemist.model.interfaces.environments.PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html).



## Constructors


| | |
|---|---|
| [CircleNode](-circle-node.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html)> [CircleNode](-circle-node.html)(env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 5.0) |


## Functions


| Name | Summary |
|---|---|
| [addReaction](../-homogeneous-physical-pedestrian2-d/index.html#-1914162920%2FFunctions%2F-134779887) | [jvm]<br>override fun [addReaction](../-homogeneous-physical-pedestrian2-d/index.html#-1914162920%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneNode](../-homogeneous-physical-pedestrian2-d/index.html#1410251741%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [AbstractNode](../-abstract-node/index.html)<[T](index.html)> |
| [compareTo](../-homogeneous-physical-pedestrian2-d/index.html#-635306233%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](../-homogeneous-physical-pedestrian2-d/index.html#-635306233%2FFunctions%2F-134779887)(@NotNull()other: @NotNull()[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887) | [jvm]<br>open operator override fun [contains](../-homogeneous-physical-pedestrian2-d/index.html#-1500024274%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](../-homogeneous-physical-pedestrian2-d/index.html#1855273807%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../-homogeneous-physical-pedestrian2-d/index.html#1514566078%2FFunctions%2F-134779887) | [jvm]<br>override fun [forEach](../-homogeneous-physical-pedestrian2-d/index.html#1514566078%2FFunctions%2F-134779887)(p0: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<in [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>>) |
| [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-989109866%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [T](index.html) |
| [getContents](../-abstract-node/get-contents.html) | [jvm]<br>open override fun [getContents](../-abstract-node/get-contents.html)(): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), [T](index.html)> |
| [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887) | [jvm]<br>override fun [getId](../-homogeneous-physical-pedestrian2-d/index.html#2063123767%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMoleculeCount](../-abstract-node/get-molecule-count.html) | [jvm]<br>open override fun [getMoleculeCount](../-abstract-node/get-molecule-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887) | [jvm]<br>override fun [getReactions](../-homogeneous-physical-pedestrian2-d/index.html#-301186114%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [hashCode](../-abstract-node/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-node/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterator](../-abstract-node/iterator.html) | [jvm]<br>operator override fun [iterator](../-abstract-node/iterator.html)(): [MutableIterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-iterator/index.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887) | [jvm]<br>open override fun [removeConcentration](../-homogeneous-physical-pedestrian2-d/index.html#571173562%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887) | [jvm]<br>override fun [removeReaction](../-homogeneous-physical-pedestrian2-d/index.html#982079025%2FFunctions%2F-134779887)(p0: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>) |
| [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConcentration](../-homogeneous-physical-pedestrian2-d/index.html#-1479666879%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [spliterator](../-abstract-node/spliterator.html) | [jvm]<br>override fun [spliterator](../-abstract-node/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> |
| [toString](../-abstract-node/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-node/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [shape](shape.html) | [jvm]<br>override val [shape](shape.html): [GeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html)><br>{@inheritDoc}. |

