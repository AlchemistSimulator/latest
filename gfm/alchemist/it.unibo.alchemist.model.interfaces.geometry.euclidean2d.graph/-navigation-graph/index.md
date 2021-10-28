//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph](../index.md)/[NavigationGraph](index.md)

# NavigationGraph

[jvm]\
interface [NavigationGraph](index.md)<[V](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[V](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[V](index.md)>, [N](index.md) : [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)<[V](index.md), [A](index.md)>, [E](index.md)> : Graph<[N](index.md), [E](index.md)> 

A graph used for navigation purposes. Nodes are [ConvexGeometricShape](../../it.unibo.alchemist.model.interfaces.geometry/-convex-geometric-shape/index.md)s, usually representing portions of an environment which are traversable by agents (the advantage of such representation is that agents can freely walk around within a convex area, as it is guaranteed that no obstacle will be found). Note that implementations of this graph must guarantee predictable ordering for the collections they maintain, as reproducibility is a key feature of Alchemist. Be also aware that, by contract, the org.jgrapht.Graph interface does not allow duplicated edges (see org.jgrapht.Graph.addEdge).

## Parameters

jvm

| | |
|---|---|
| V | the [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) type for the space this graph describes. |
| A | the transformations supported by shapes in this space. |
| N | the type of nodes (or vertices). |
| E | the type of edges. |

## Functions

| Name | Summary |
|---|---|
| [addEdge](index.md#2110871166%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addEdge](index.md#2110871166%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [E](index.md)<br>abstract fun [addEdge](index.md#521958941%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md), p2: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addVertex](index.md#-2135174814%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [addVertex](index.md#-2135174814%2FFunctions%2F-267951372)(): [N](index.md)<br>abstract fun [addVertex](index.md#2101592049%2FFunctions%2F-267951372)(p0: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsEdge](index.md#794769479%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [containsEdge](index.md#794769479%2FFunctions%2F-267951372)(p0: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [containsEdge](index.md#-1271913840%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsVertex](index.md#-309293565%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [containsVertex](index.md#-309293565%2FFunctions%2F-267951372)(p0: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [degreeOf](index.md#-547757405%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [degreeOf](index.md#-547757405%2FFunctions%2F-267951372)(p0: [N](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [edgeSet](index.md#1973462050%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [edgeSet](index.md#1973462050%2FFunctions%2F-267951372)(): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [edgesOf](index.md#-810360679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [edgesOf](index.md#-810360679%2FFunctions%2F-267951372)(p0: [N](index.md)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [getAllEdges](index.md#-302918485%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getAllEdges](index.md#-302918485%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [getEdge](index.md#-1210728653%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getEdge](index.md#-1210728653%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [E](index.md) |
| [getEdgeSource](index.md#1251874021%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getEdgeSource](index.md#1251874021%2FFunctions%2F-267951372)(p0: [E](index.md)): [N](index.md) |
| [getEdgeSupplier](index.md#531722152%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getEdgeSupplier](index.md#531722152%2FFunctions%2F-267951372)(): [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[E](index.md)> |
| [getEdgeTarget](index.md#806962267%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getEdgeTarget](index.md#806962267%2FFunctions%2F-267951372)(p0: [E](index.md)): [N](index.md) |
| [getEdgeWeight](index.md#1196438594%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getEdgeWeight](index.md#1196438594%2FFunctions%2F-267951372)(p0: [E](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getType](index.md#-14194633%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getType](index.md#-14194633%2FFunctions%2F-267951372)(): GraphType |
| [getVertexSupplier](index.md#1053669281%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getVertexSupplier](index.md#1053669281%2FFunctions%2F-267951372)(): [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[N](index.md)> |
| [incomingEdgesOf](index.md#-522787565%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [incomingEdgesOf](index.md#-522787565%2FFunctions%2F-267951372)(p0: [N](index.md)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [inDegreeOf](index.md#-739572952%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [inDegreeOf](index.md#-739572952%2FFunctions%2F-267951372)(p0: [N](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [iterables](index.md#-245102522%2FFunctions%2F-267951372) | [jvm]<br>open fun [iterables](index.md#-245102522%2FFunctions%2F-267951372)(): GraphIterables<[N](index.md), [E](index.md)> |
| [nodeContaining](node-containing.md) | [jvm]<br>open fun [nodeContaining](node-containing.md)(position: [V](index.md)): [N](index.md)? |
| [outDegreeOf](index.md#1223323901%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [outDegreeOf](index.md#1223323901%2FFunctions%2F-267951372)(p0: [N](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [outgoingEdgesOf](index.md#-297762675%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [outgoingEdgesOf](index.md#-297762675%2FFunctions%2F-267951372)(p0: [N](index.md)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [removeAllEdges](index.md#1282760498%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeAllEdges](index.md#1282760498%2FFunctions%2F-267951372)(p0: [MutableCollection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-collection/index.html)<out [E](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [removeAllEdges](index.md#519568877%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[E](index.md)> |
| [removeAllVertices](index.md#-1435029466%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeAllVertices](index.md#-1435029466%2FFunctions%2F-267951372)(p0: [MutableCollection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-collection/index.html)<out [N](index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeEdge](index.md#1206013868%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeEdge](index.md#1206013868%2FFunctions%2F-267951372)(p0: [E](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>abstract fun [removeEdge](index.md#525785461%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md)): [E](index.md) |
| [removeVertex](index.md#-1464647192%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [removeVertex](index.md#-1464647192%2FFunctions%2F-267951372)(p0: [N](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setEdgeWeight](index.md#-520824077%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [setEdgeWeight](index.md#-520824077%2FFunctions%2F-267951372)(p0: [E](index.md), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>open fun [setEdgeWeight](index.md#870159356%2FFunctions%2F-267951372)(p0: [N](index.md), p1: [N](index.md), p2: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [vertexSet](index.md#-845040375%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [vertexSet](index.md#-845040375%2FFunctions%2F-267951372)(): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[N](index.md)> |

## Inheritors

| Name |
|---|
| [BaseNavigationGraph](../../it.unibo.alchemist.model.implementations.geometry.euclidean2d.graph/-base-navigation-graph/index.md) |
