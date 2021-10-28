---
title: AbstractNavigationAction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractNavigationAction](index.html)/[AbstractNavigationAction](-abstract-navigation-action.html)



# AbstractNavigationAction



[jvm]\
fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [L](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [R](index.html), [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[P](index.html), [A](index.html)>, [E](index.html)> [AbstractNavigationAction](-abstract-navigation-action.html)(environment: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.html)<*, [T](index.html), [P](index.html), [A](index.html), [N](index.html), [E](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, pedestrian: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.html)<[T](index.html), [P](index.html), [A](index.html), [L](index.html), [R](index.html)>)



## Parameters


jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.html)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |




