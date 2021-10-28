//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[MapEnvironment](index.md)/[computeRoute](compute-route.md)

# computeRoute

[jvm]\
abstract fun [computeRoute](compute-route.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.md)>, node2: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.md)>): [Route](../-route/index.md)<[GeoPosition](../-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.md) calling this method to effectively move nodes along the path. It uses the fastest path as metric.

#### Return

A [Route](../-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The start node |
| node2 | the second node's position will be used as destination |

[jvm]\
abstract fun [computeRoute](compute-route.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.md)>, coord: [GeoPosition](../-geo-position/index.md)): [Route](../-route/index.md)<[GeoPosition](../-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The [Node](../-node/index.md) to move |
| coord | The absolute coordinate where this node wants to move to |

[jvm]\
abstract fun [computeRoute](compute-route.md)(node: [Node](../-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.routing/-on-streets/index.md)>, coord: [GeoPosition](../-geo-position/index.md), vehicle: [Vehicle](../-vehicle/index.md)): [Route](../-route/index.md)<[GeoPosition](../-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The [Node](../-node/index.md) to move |
| coord | The absolute coordinate where this node wants to move to |
| vehicle | The vehicle tipe for this route |

[jvm]\
abstract fun [computeRoute](compute-route.md)(p1: [GeoPosition](../-geo-position/index.md), p2: [GeoPosition](../-geo-position/index.md)): [Route](../-route/index.md)<[GeoPosition](../-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |

[jvm]\
abstract fun [computeRoute](compute-route.md)(p1: [GeoPosition](../-geo-position/index.md), p2: [GeoPosition](../-geo-position/index.md), vehicle: [Vehicle](../-vehicle/index.md)): [Route](../-route/index.md)<[GeoPosition](../-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |
| vehicle | vehicle to use. Different vehicles may use different paths, e.g. pedestrians can't go along a highway, but can walk the parks |
