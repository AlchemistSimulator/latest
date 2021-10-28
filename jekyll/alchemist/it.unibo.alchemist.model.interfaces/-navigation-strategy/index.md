---
title: NavigationStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[NavigationStrategy](index.html)



# NavigationStrategy



[jvm]\
interface [NavigationStrategy](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [R](index.html), [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html)>

Defines what a pedestrian should do when in a new room (= environment's area), this is designed to be used jointly with a [NavigationAction](../-navigation-action/index.html): the latter defines how to properly move the pedestrian, while delegating the decision on where to move it to a [NavigationStrategy](index.html).



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |



## Functions


| Name | Summary |
|---|---|
| [inNewRoom](in-new-room.html) | [jvm]<br>abstract fun [inNewRoom](in-new-room.html)(newRoom: [N](index.html))<br>This is called whenever the pedestrian enters a new room. |
| [inUnexpectedNewRoom](in-unexpected-new-room.html) | [jvm]<br>open fun [inUnexpectedNewRoom](in-unexpected-new-room.html)(previousRoom: [N](index.html), expectedNewRoom: [N](index.html), actualNewRoom: [N](index.html))<br>This is called in place of [inNewRoom](in-new-room.html) when the pedestrian ends up in an unexpected room while moving. |


## Properties


| Name | Summary |
|---|---|
| [action](action.html) | [jvm]<br>abstract val [action](action.html): [NavigationAction](../-navigation-action/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html), [N](index.html), [E](index.html)><br>The [NavigationAction](../-navigation-action/index.html) used to navigate the environment. |


## Inheritors


| Name |
|---|
| [Exploring](../../it.unibo.alchemist.model.implementations.actions.navigationstrategies/-exploring/index.html) |

