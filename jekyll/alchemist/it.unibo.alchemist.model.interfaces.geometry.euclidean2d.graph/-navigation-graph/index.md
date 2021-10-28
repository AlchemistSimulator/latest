---
title: NavigationGraph
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](../index.html)/[NavigationGraph](index.html)



# NavigationGraph



[jvm]\
interface [NavigationGraph](index.html)<[V](index.html) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](index.html)>, [N](index.html) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)<[V](index.html), [A](index.html)>, [E](index.html)> : Graph<[N](index.html), [E](index.html)> 

A graph used for navigation purposes. Nodes are [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.html)s, usually representing portions of an environment which are traversable by agents (the advantage of such representation is that agents can freely walk around within a convex area, as it is guaranteed that no obstacle will be found). Note that implementations of this graph must guarantee predictable ordering for the collections they maintain, as reproducibility is a key feature of Alchemist. Be also aware that, by contract, the org.jgrapht.Graph interface does not allow duplicated edges (see org.jgrapht.Graph.addEdge).



## Parameters


jvm

| | |
|---|---|
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) type for the space this graph describes. |
| A | the transformations supported by shapes in this space. |
| N | the type of nodes (or vertices). |
| E | the type of edges. |



## Functions


| Name | Summary |
|---|---|
| [addEdge](index.html#2110871166%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addEdge](index.html#2110871166%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [E](index.html)<br>abstract fun [addEdge](index.html#521958941%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html), p2: [E](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addVertex](index.html#-2135174814%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addVertex](index.html#-2135174814%2FFunctions%2F-134779887)(): [N](index.html)<br>abstract fun [addVertex](index.html#2101592049%2FFunctions%2F-134779887)(p0: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsEdge](index.html#794769479%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [containsEdge](index.html#794769479%2FFunctions%2F-134779887)(p0: [E](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [containsEdge](index.html#-1271913840%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsVertex](index.html#-309293565%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [containsVertex](index.html#-309293565%2FFunctions%2F-134779887)(p0: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [degreeOf](index.html#-547757405%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [degreeOf](index.html#-547757405%2FFunctions%2F-134779887)(p0: [N](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [edgeSet](index.html#1973462050%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [edgeSet](index.html#1973462050%2FFunctions%2F-134779887)(): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [edgesOf](index.html#-810360679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [edgesOf](index.html#-810360679%2FFunctions%2F-134779887)(p0: [N](index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [getAllEdges](index.html#-302918485%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getAllEdges](index.html#-302918485%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [getEdge](index.html#-1210728653%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getEdge](index.html#-1210728653%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [E](index.html) |
| [getEdgeSource](index.html#1251874021%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getEdgeSource](index.html#1251874021%2FFunctions%2F-134779887)(p0: [E](index.html)): [N](index.html) |
| [getEdgeSupplier](index.html#531722152%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getEdgeSupplier](index.html#531722152%2FFunctions%2F-134779887)(): [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[E](index.html)> |
| [getEdgeTarget](index.html#806962267%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getEdgeTarget](index.html#806962267%2FFunctions%2F-134779887)(p0: [E](index.html)): [N](index.html) |
| [getEdgeWeight](index.html#1196438594%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getEdgeWeight](index.html#1196438594%2FFunctions%2F-134779887)(p0: [E](index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getType](index.html#-14194633%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getType](index.html#-14194633%2FFunctions%2F-134779887)(): GraphType |
| [getVertexSupplier](index.html#1053669281%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getVertexSupplier](index.html#1053669281%2FFunctions%2F-134779887)(): [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[N](index.html)> |
| [incomingEdgesOf](index.html#-522787565%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [incomingEdgesOf](index.html#-522787565%2FFunctions%2F-134779887)(p0: [N](index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [inDegreeOf](index.html#-739572952%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [inDegreeOf](index.html#-739572952%2FFunctions%2F-134779887)(p0: [N](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterables](index.html#-245102522%2FFunctions%2F-134779887) | [jvm]<br>open fun [iterables](index.html#-245102522%2FFunctions%2F-134779887)(): GraphIterables<[N](index.html), [E](index.html)> |
| [nodeContaining](node-containing.html) | [jvm]<br>open fun [nodeContaining](node-containing.html)(position: [V](index.html)): [N](index.html)? |
| [outDegreeOf](index.html#1223323901%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [outDegreeOf](index.html#1223323901%2FFunctions%2F-134779887)(p0: [N](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [outgoingEdgesOf](index.html#-297762675%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [outgoingEdgesOf](index.html#-297762675%2FFunctions%2F-134779887)(p0: [N](index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [removeAllEdges](index.html#1282760498%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeAllEdges](index.html#1282760498%2FFunctions%2F-134779887)(p0: [MutableCollection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-collection/index.html)<out [E](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [removeAllEdges](index.html#519568877%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.html)> |
| [removeAllVertices](index.html#-1435029466%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeAllVertices](index.html#-1435029466%2FFunctions%2F-134779887)(p0: [MutableCollection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-collection/index.html)<out [N](index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeEdge](index.html#1206013868%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeEdge](index.html#1206013868%2FFunctions%2F-134779887)(p0: [E](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [removeEdge](index.html#525785461%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html)): [E](index.html) |
| [removeVertex](index.html#-1464647192%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeVertex](index.html#-1464647192%2FFunctions%2F-134779887)(p0: [N](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setEdgeWeight](index.html#-520824077%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [setEdgeWeight](index.html#-520824077%2FFunctions%2F-134779887)(p0: [E](index.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>open fun [setEdgeWeight](index.html#870159356%2FFunctions%2F-134779887)(p0: [N](index.html), p1: [N](index.html), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [vertexSet](index.html#-845040375%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [vertexSet](index.html#-845040375%2FFunctions%2F-134779887)(): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[N](index.html)> |


## Inheritors


| Name |
|---|
| [BaseNavigationGraph](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d.graph/-base-navigation-graph/index.html) |

