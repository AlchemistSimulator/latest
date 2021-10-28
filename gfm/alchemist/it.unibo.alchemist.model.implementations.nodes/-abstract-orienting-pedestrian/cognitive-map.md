//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractOrientingPedestrian](index.md)/[cognitiveMap](cognitive-map.md)

# cognitiveMap

[jvm]\
open override val [cognitiveMap](cognitive-map.md): [NavigationGraph](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d.graph/-navigation-graph/index.md)<[P](index.md), [A](index.md), [L](index.md), DefaultEdge>

The cognitive map of the pedestrian. This is generated from the [environment](index.md#322801955%2FProperties%2F-267951372)'s graph as follows: we randomly select a % of environment's areas equal to the knowledge degree of the pedestrian, we then create a landmark in each of them. Those landmarks will be the nodes of the cognitive map. Concerning the connections between them, we produce a graph in which each generated landmark is connected to any other landmark reachable from it, with an edge whose weight depends on the number of areas that need to be traversed. Finally, the cognitive map is a minimum spanning tree of the described full connected graph. Note that edges are plain DefaultEdges, which means no extra info regarding the connection between landmarks is stored in the cognitive map. If two landmarks are connected, the pedestrian knows there's a path between them (this may be simple or not, i.e. representable as a single segment, but the pedestrian doesn't know it). If two landmarks are not connected, the pedestrian doesn't have info regarding any path between them, which may anyway exist.
