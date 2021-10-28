//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.groups](../index.md)/[Alone](index.md)

# Alone

[jvm]\
class [Alone](index.md)<[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>>(**pedestrian**: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>) : [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [S](index.md), [A](index.md)> 

Group representing a pedestrian alone.

## Constructors

| | |
|---|---|
| [Alone](-alone.md) | [jvm]<br>fun <[T](index.md), [S](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[S](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[S](index.md)>> [Alone](-alone.md)(pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [addMember](add-member.md) | [jvm]<br>open override fun [addMember](add-member.md)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [S](index.md), [A](index.md)><br>Add a node in this group if not already part of it. |
| [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md#-1711138971%2FFunctions%2F-267951372) | [jvm]<br>open fun [contains](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md#-1711138971%2FFunctions%2F-267951372)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether a node belongs to this group or not. |
| [removeMember](remove-member.md) | [jvm]<br>open override fun [removeMember](remove-member.md)(node: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>): [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [S](index.md), [A](index.md)><br>Remove a node from this group. |

## Properties

| Name | Summary |
|---|---|
| [members](members.md) | [jvm]<br>open override val [members](members.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [S](index.md), [A](index.md)>><br>The list of pedestrians belonging to this group. |
