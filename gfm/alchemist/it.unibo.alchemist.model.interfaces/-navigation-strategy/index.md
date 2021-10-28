//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[NavigationStrategy](index.md)

# NavigationStrategy

[jvm]\
interface [NavigationStrategy](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [R](index.md), [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md)>

Defines what a pedestrian should do when in a new room (= environment's area), this is designed to be used jointly with a [NavigationAction](../-navigation-action/index.md): the latter defines how to properly move the pedestrian, while delegating the decision on where to move it to a [NavigationStrategy](index.md).

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../-position/index.md) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |

## Functions

| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.md) | [jvm]<br>abstract fun [inNewRoom](in-new-room.md)(newRoom: [N](index.md))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](in-unexpected-new-room.md) | [jvm]<br>open fun [inUnexpectedNewRoom](in-unexpected-new-room.md)(previousRoom: [N](index.md), expectedNewRoom: [N](index.md), actualNewRoom: [N](index.md))<br>This is called in place of [inNewRoom](in-new-room.md) when the pedestrian ends up in an unexpected room while moving. |

## Properties

| Name | Summary |
|---|---|
| [action](action.md) | [jvm]<br>abstract val [action](action.md): [NavigationAction](../-navigation-action/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md), [N](index.md), [E](index.md)><br>The [NavigationAction](../-navigation-action/index.md) used to navigate the environment. |

## Inheritors

| Name |
|---|
| [Exploring](../../it.unibo.alchemist.model.implementations.actions.navigationstrategies/-exploring/index.md) |
