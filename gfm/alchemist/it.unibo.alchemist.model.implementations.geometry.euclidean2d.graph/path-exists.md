//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.graph](index.md)/[pathExists](path-exists.md)

# pathExists

[jvm]\
fun <[V](path-exists.md)> Graph<[V](path-exists.md), *>.[pathExists](path-exists.md)(source: [V](path-exists.md), sink: [V](path-exists.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Checks whether a path exists between [source](path-exists.md) and [sink](path-exists.md). DijkstraShortestPath is used instead of org.jgrapht.alg.connectivity.ConnectivityInspector.pathExists, because, in case of directed graph, the latter checks whether the given vertices lay in the same weakly connected component, which is not the desired behavior. As unweighted graphs have a default edge weight of 1.0, shortest path algorithms can always be applied meaningfully.
