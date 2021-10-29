---
title: generateNavigationGraph
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.navigator](index.html)/[generateNavigationGraph](generate-navigation-graph.html)



# generateNavigationGraph



[jvm]\
fun [generateNavigationGraph](generate-navigation-graph.html)(origin: [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html) = Euclidean2DPosition(0.0, 0.0), width: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), height: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), obstacles: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Shape](https://docs.oracle.com/javase/8/docs/api/java/awt/Shape.html)>, rooms: [Collection](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-collection/index.html)<[Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, unity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0): [Euclidean2DNavigationGraph](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/index.html#-513689941%2FClasslikes%2F-134779887)



TODO(improve the quality of this algorithm) NaviGator (Navigation Graphs Generator) is an algorithm capable of generating an [Euclidean2DNavigationGraph](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/index.html#-513689941%2FClasslikes%2F-134779887) of a given environment with obstacles. The nodes of the produced graph are convex polygons representing the areas of the environment traversable by agents (namely, walkable areas), whereas edges represent connections between them.



NaviGator works with rectangular-shaped bidimensional environments with euclidean geometry and double precision coordinates. Note that this algorithm:



<ul><li>does not guarantee the coverage of 100% of the walkable area.</li><li>is only capable to deal with convex polygonal obstacles (concave ones can be decomposed into convex meshes, whereas for curves bounding boxes can be used).</li><li>is only capable to detect axis-aligned crossings.</li><li>can take a significant amount of time to generate a navigation graph.</li></ul>



Here's a brief description of how the algorithm operates: Firstly, a certain number of seeds is planted in the environment. Each seed is a square-shaped region of unitary side that will grow maintaining a convex shape. Secondly, planted seeds are extended until possible (i.e. until they are in contact with an obstacle or another seed on each side). Finally, crossings are found between the grown seeds.



## Parameters


jvm

| | |
|---|---|
| origin | the origin of the environment, defaults to (0,0). |
| width | the width of the environment (only positive). |
| height | the height of the environment (only positive). |
| obstacles | the obstacles of the environment (only convex polygonal obstacles     are supported). |
| rooms | a collection of positions where to plant initial seeds. In indoor     environments, these positions are usually located inside rooms     (and corridors), hence the name of the parameter. |
| unity | the quantity considered to be a unit in the environment (defaults     to 1.0 because this algorithm works best with environments featuring     integer coordinates). In the growing phase, each side of each seed     will be advanced of a quantity equal to unity iteratively, hence the     smaller this value is the slower the algorithm will be. |




