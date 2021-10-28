//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractNavigationAction](index.md)/[AbstractNavigationAction](-abstract-navigation-action.md)

# AbstractNavigationAction

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [L](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [R](index.md), [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[P](index.md), [A](index.md)>, [E](index.md)> [AbstractNavigationAction](-abstract-navigation-action.md)(environment: [EnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-environment-with-graph/index.md)<*, [T](index.md), [P](index.md), [A](index.md), [N](index.md), [E](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [OrientingPedestrian](../../it.unibo.alchemist.model.interfaces/-orienting-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md), [L](index.md), [R](index.md)>)

## Parameters

jvm

| | |
|---|---|
| T | the concentration type. |
| P | the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type and [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space the pedestrian is into. |
| A | the transformations supported by the shapes in this space. |
| L | the type of landmarks of the pedestrian's cognitive map. |
| R | the type of edges of the pedestrian's cognitive map, representing the [R](index.md)elations between landmarks. |
| N | the type of nodes of the navigation graph provided by the environment. |
| E | the type of edges of the navigation graph provided by the environment. |
