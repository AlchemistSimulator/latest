---
title: pathExists
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.geometry.euclidean2d.graph](index.html)/[pathExists](path-exists.html)



# pathExists



[jvm]\
fun <[V](path-exists.html)> Graph<[V](path-exists.html), *>.[pathExists](path-exists.html)(source: [V](path-exists.html), sink: [V](path-exists.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Checks whether a path exists between [source](path-exists.html) and [sink](path-exists.html). DijkstraShortestPath is used instead of org.jgrapht.alg.connectivity.ConnectivityInspector.pathExists, because, in case of directed graph, the latter checks whether the given vertices lay in the same weakly connected component, which is not the desired behavior. As unweighted graphs have a default edge weight of 1.0, shortest path algorithms can always be applied meaningfully.




