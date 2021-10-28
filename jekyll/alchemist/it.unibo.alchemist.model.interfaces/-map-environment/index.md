---
title: MapEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[MapEnvironment](index.html)



# MapEnvironment



[jvm]\
interface [MapEnvironment](index.html)<[T](index.html)> : [BenchmarkableEnvironment](../-benchmarkable-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../-geo-position/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Functions


| Name | Summary |
|---|---|
| [addLayer](../-environment/add-layer.html) | [jvm]<br>abstract fun [addLayer](../-environment/add-layer.html)(p: [Molecule](../-molecule/index.html), p1: [Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [addNode](../-environment/add-node.html) | [jvm]<br>abstract fun [addNode](../-environment/add-node.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, p1: [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)) |
| [addTerminator](../-environment/add-terminator.html) | [jvm]<br>abstract fun [addTerminator](../-environment/add-terminator.html)(p: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>>) |
| [computeRoute](compute-route.html) | [jvm]<br>abstract fun [computeRoute](compute-route.html)(p1: [GeoPosition](../-geo-position/index.html), p2: [GeoPosition](../-geo-position/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)><br>abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, coord: [GeoPosition](../-geo-position/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)><br>abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, node2: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)><br>abstract fun [computeRoute](compute-route.html)(p1: [GeoPosition](../-geo-position/index.html), p2: [GeoPosition](../-geo-position/index.html), vehicle: [Vehicle](../-vehicle/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)><br>abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, coord: [GeoPosition](../-geo-position/index.html), vehicle: [Vehicle](../-vehicle/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)><br>This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. |
| [enableBenchmark](../-benchmarkable-environment/enable-benchmark.html) | [jvm]<br>abstract fun [enableBenchmark](../-benchmarkable-environment/enable-benchmark.html)() |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getBenchmarkResult](../-benchmarkable-environment/get-benchmark-result.html) | [jvm]<br>abstract fun [getBenchmarkResult](../-benchmarkable-environment/get-benchmark-result.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getDimensions](../-environment/get-dimensions.html) | [jvm]<br>abstract fun [getDimensions](../-environment/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.html) | [jvm]<br>abstract fun [getDistanceBetweenNodes](../-environment/get-distance-between-nodes.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, p1: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](../-environment/get-incarnation.html) | [jvm]<br>abstract fun [getIncarnation](../-environment/get-incarnation.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLayer](../-environment/get-layer.html) | [jvm]<br>abstract fun [getLayer](../-environment/get-layer.html)(p: [Molecule](../-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLayers](../-environment/get-layers.html) | [jvm]<br>abstract fun [getLayers](../-environment/get-layers.html)(): ListSet<[Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLinkingRule](../-environment/get-linking-rule.html) | [jvm]<br>abstract fun [getLinkingRule](../-environment/get-linking-rule.html)(): [LinkingRule](../-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |
| [getNeighborhood](../-environment/get-neighborhood.html) | [jvm]<br>abstract fun [getNeighborhood](../-environment/get-neighborhood.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Neighborhood](../-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [getNodeByID](../-environment/get-node-by-i-d.html) | [jvm]<br>abstract fun [getNodeByID](../-environment/get-node-by-i-d.html)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [getNodeCount](../-environment/get-node-count.html) | [jvm]<br>abstract fun [getNodeCount](../-environment/get-node-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../-environment/get-nodes.html) | [jvm]<br>abstract fun [getNodes](../-environment/get-nodes.html)(): ListSet<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>> |
| [getNodesWithinRange](../-environment/get-nodes-within-range.html) | [jvm]<br>abstract fun [getNodesWithinRange](../-environment/get-nodes-within-range.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>> |
| [getOffset](../-environment/get-offset.html) | [jvm]<br>abstract fun [getOffset](../-environment/get-offset.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getPosition](../-environment/get-position.html) | [jvm]<br>abstract fun [getPosition](../-environment/get-position.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [getSimulation](../-environment/get-simulation.html) | [jvm]<br>abstract fun [getSimulation](../-environment/get-simulation.html)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |
| [getSize](../-environment/get-size.html) | [jvm]<br>abstract fun [getSize](../-environment/get-size.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.html) | [jvm]<br>abstract fun [getSizeInDistanceUnits](../-environment/get-size-in-distance-units.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [isTerminated](../-environment/is-terminated.html) | [jvm]<br>abstract fun [isTerminated](../-environment/is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [makePosition](../-environment/make-position.html) | [jvm]<br>abstract fun [makePosition](../-environment/make-position.html)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [moveNodeToPosition](../-environment/move-node-to-position.html) | [jvm]<br>abstract fun [moveNodeToPosition](../-environment/move-node-to-position.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, p1: [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)) |
| [removeNode](../-environment/remove-node.html) | [jvm]<br>abstract fun [removeNode](../-environment/remove-node.html)(p: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>) |
| [setLinkingRule](../-environment/set-linking-rule.html) | [jvm]<br>abstract fun [setLinkingRule](../-environment/set-linking-rule.html)(p: [LinkingRule](../-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [setSimulation](../-environment/set-simulation.html) | [jvm]<br>abstract fun [setSimulation](../-environment/set-simulation.html)(p: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_VEHICLE](-d-e-f-a-u-l-t_-v-e-h-i-c-l-e.html) | [jvm]<br>val [DEFAULT_VEHICLE](-d-e-f-a-u-l-t_-v-e-h-i-c-l-e.html): [Vehicle](../-vehicle/index.html)<br>The default vehicle. |


## Inheritors


| Name |
|---|
| [OSMEnvironment](../../it.unibo.alchemist.model.implementations.environments/-o-s-m-environment/index.html) |

