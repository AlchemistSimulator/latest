---
title: it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](index.html)



# Package it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph



## Types


| Name | Summary |
|---|---|
| [Euclidean2DNavigationGraph](index.html#-513689941%2FClasslikes%2F-134779887) | [jvm]<br>typealias [Euclidean2DNavigationGraph](index.html#-513689941%2FClasslikes%2F-134779887) = [NavigationGraph](-navigation-graph/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), [Euclidean2DPassage](-euclidean2-d-passage/index.html)><br>A [NavigationGraph](-navigation-graph/index.html) in an euclidean bidimensional space. Nodes are [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)s and edges are [Euclidean2DPassage](-euclidean2-d-passage/index.html)s. Using [Euclidean2DPassage](-euclidean2-d-passage/index.html)s as edges leads to some overhead (as these store the nodes they connect, when this information is already stored in the navigation graph), but allows to have duplicate edges in opposite directions, which means a node n1 can be connected to another node n2 through a passage whose shape is equal to the one of the passage connecting n2 to n1. The two passages would not result equal because their tail and head would be swapped. On the contrary, if edges were plain segments, the graph would not have allowed to have two edges so that e1.equal(e2). |
| [Euclidean2DPassage](-euclidean2-d-passage/index.html) | [jvm]<br>data class [Euclidean2DPassage](-euclidean2-d-passage/index.html)(**tail**: [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), **head**: [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html), **passageShapeOnTail**: [Segment2D](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-segment2-d/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>)<br>Defines a passage between two [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)s in an euclidean bidimensional space. |
| [NavigationGraph](-navigation-graph/index.html) | [jvm]<br>interface [NavigationGraph](-navigation-graph/index.html)<[V](-navigation-graph/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](-navigation-graph/index.html)>, [A](-navigation-graph/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](-navigation-graph/index.html)>, [N](-navigation-graph/index.html) : [ConvexGeometricShape](../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](-navigation-graph/index.html), [A](-navigation-graph/index.html)>, [E](-navigation-graph/index.html)> : Graph<[N](-navigation-graph/index.html), [E](-navigation-graph/index.html)> <br>A graph used for navigation purposes. |

