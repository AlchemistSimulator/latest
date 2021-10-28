---
title: OSMEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[OSMEnvironment](index.html)



# OSMEnvironment



[jvm]\
class [OSMEnvironment](index.html)<[T](index.html)> : [Abstract2DEnvironment](../-abstract2-d-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> , [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> 

This class serves as template for more specific implementations of environments using a map. It encloses the navigation logic, but leaves the subclasses to decide how to provide map data (e.g. loading from disk or rely on online services). The data is then stored in-memory for performance reasons.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>)<br>Builds a new [OSMEnvironment](index.html) without an actual backing map. |
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Builds a new [OSMEnvironment](index.html), with nodes not forced on streets. |
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the incarnation to be used. |
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), onlyOnStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the incarnation to be used. |
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), approximation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>the incarnation to be used. |
| [OSMEnvironment](-o-s-m-environment.html) | [jvm]<br>open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), approximation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), onlyOnStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the incarnation to be used. |


## Functions


| Name | Summary |
|---|---|
| [addLayer](../-abstract-environment/add-layer.html) | [jvm]<br>fun [addLayer](../-abstract-environment/add-layer.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), l: [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [addNode](../-abstract-environment/add-node.html) | [jvm]<br>fun [addNode](../-abstract-environment/add-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, p: [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)) |
| [addTerminator](../-abstract-environment/add-terminator.html) | [jvm]<br>fun [addTerminator](../-abstract-environment/add-terminator.html)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>>) |
| [computeRoute](compute-route.html) | [jvm]<br>open fun [computeRoute](compute-route.html)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)><br>open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)><br>open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, node2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)><br>open fun [computeRoute](compute-route.html)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)><br>open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)><br>This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. |
| [enableBenchmark](enable-benchmark.html) | [jvm]<br>open fun [enableBenchmark](enable-benchmark.html)() |
| [forEach](../-abstract-environment/for-each.html) | [jvm]<br>fun [forEach](../-abstract-environment/for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getBenchmarkResult](get-benchmark-result.html) | [jvm]<br>open fun [getBenchmarkResult](get-benchmark-result.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getDimensions](../-abstract2-d-environment/get-dimensions.html) | [jvm]<br>fun [getDimensions](../-abstract2-d-environment/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](../-abstract-environment/get-distance-between-nodes.html) | [jvm]<br>fun [getDistanceBetweenNodes](../-abstract-environment/get-distance-between-nodes.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](index.html#-2029827470%2FFunctions%2F-134779887) | [jvm]<br>fun [getIncarnation](index.html#-2029827470%2FFunctions%2F-134779887)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLayer](../-abstract-environment/get-layer.html) | [jvm]<br>fun [getLayer](../-abstract-environment/get-layer.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLayers](index.html#-111627440%2FFunctions%2F-134779887) | [jvm]<br>fun [getLayers](index.html#-111627440%2FFunctions%2F-134779887)(): ListSet<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>> |
| [getLinkingRule](../-abstract-environment/get-linking-rule.html) | [jvm]<br>fun [getLinkingRule](../-abstract-environment/get-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |
| [getNeighborhood](../-abstract-environment/get-neighborhood.html) | [jvm]<br>fun [getNeighborhood](../-abstract-environment/get-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [getNodeByID](../-abstract-environment/get-node-by-i-d.html) | [jvm]<br>fun [getNodeByID](../-abstract-environment/get-node-by-i-d.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [getNodeCount](../-abstract-environment/get-node-count.html) | [jvm]<br>fun [getNodeCount](../-abstract-environment/get-node-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](index.html#-1850356489%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodes](index.html#-1850356489%2FFunctions%2F-134779887)(): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>> |
| [getNodesWithinRange](../-abstract-environment/get-nodes-within-range.html) | [jvm]<br>fun [getNodesWithinRange](../-abstract-environment/get-nodes-within-range.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>> |
| [getOffset](../-abstract2-d-environment/get-offset.html) | [jvm]<br>fun [getOffset](../-abstract2-d-environment/get-offset.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getPosition](../-abstract-environment/get-position.html) | [jvm]<br>open fun [getPosition](../-abstract-environment/get-position.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>): [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html) |
| [getSimulation](index.html#469895083%2FFunctions%2F-134779887) | [jvm]<br>fun [getSimulation](index.html#469895083%2FFunctions%2F-134779887)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)> |
| [getSize](../-abstract2-d-environment/get-size.html) | [jvm]<br>fun [getSize](../-abstract2-d-environment/get-size.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getSizeInDistanceUnits](get-size-in-distance-units.html) | [jvm]<br>open fun [getSizeInDistanceUnits](get-size-in-distance-units.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [isTerminated](../-abstract-environment/is-terminated.html) | [jvm]<br>fun [isTerminated](../-abstract-environment/is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](../-abstract-environment/iterator.html) | [jvm]<br>fun [iterator](../-abstract-environment/iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [makePosition](make-position.html) | [jvm]<br>open fun [makePosition](make-position.html)(coordinates: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [moveNodeToPosition](../-abstract2-d-environment/move-node-to-position.html) | [jvm]<br>open fun [moveNodeToPosition](../-abstract2-d-environment/move-node-to-position.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>, newpos: [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)) |
| [removeNode](../-abstract-environment/remove-node.html) | [jvm]<br>fun [removeNode](../-abstract-environment/remove-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>) |
| [setLinkingRule](../-abstract-environment/set-linking-rule.html) | [jvm]<br>fun [setLinkingRule](../-abstract-environment/set-linking-rule.html)(r: [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [setSimulation](index.html#388221721%2FFunctions%2F-134779887) | [jvm]<br>fun [setSimulation](index.html#388221721%2FFunctions%2F-134779887)(s: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html), [P](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-ignore-streets/index.html)>) |
| [spliterator](../-abstract-environment/spliterator.html) | [jvm]<br>fun [spliterator](../-abstract-environment/spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)>><br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.html)> |
| [toString](../-abstract-environment/to-string.html) | [jvm]<br>open fun [toString](../-abstract-environment/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_ALGORITHM](-d-e-f-a-u-l-t_-a-l-g-o-r-i-t-h-m.html) | [jvm]<br>val [DEFAULT_ALGORITHM](-d-e-f-a-u-l-t_-a-l-g-o-r-i-t-h-m.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>The default routing algorithm. |
| [DEFAULT_APPROXIMATION](-d-e-f-a-u-l-t_-a-p-p-r-o-x-i-m-a-t-i-o-n.html) | [jvm]<br>val [DEFAULT_APPROXIMATION](-d-e-f-a-u-l-t_-a-p-p-r-o-x-i-m-a-t-i-o-n.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The default value for approximating the positions comparison. |
| [DEFAULT_FORCE_STREETS](-d-e-f-a-u-l-t_-f-o-r-c-e_-s-t-r-e-e-t-s.html) | [jvm]<br>val [DEFAULT_FORCE_STREETS](-d-e-f-a-u-l-t_-f-o-r-c-e_-s-t-r-e-e-t-s.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default value for the discard of nodes too far from streets option. |
| [DEFAULT_ON_STREETS](-d-e-f-a-u-l-t_-o-n_-s-t-r-e-e-t-s.html) | [jvm]<br>val [DEFAULT_ON_STREETS](-d-e-f-a-u-l-t_-o-n_-s-t-r-e-e-t-s.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>The default value for the force nodes on streets option. |
