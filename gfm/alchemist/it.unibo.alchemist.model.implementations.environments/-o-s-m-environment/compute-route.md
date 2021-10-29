//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.environments](../index.md)/[OSMEnvironment](index.md)/[computeRoute](compute-route.md)

# computeRoute

[jvm]\
open fun [computeRoute](compute-route.md)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |

[jvm]\
open fun [computeRoute](compute-route.md)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |
| vehicle | vehicle to use. Different vehicles may use different paths, e.g. pedestrians can't go along a highway, but can walk the parks |

[jvm]\
open fun [computeRoute](compute-route.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.md)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) to move |
| coord | The absolute coordinate where this node wants to move to |

[jvm]\
open fun [computeRoute](compute-route.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.md)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.md)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) calling this method to effectively move nodes along the path.

#### Return

A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md) to move |
| coord | The absolute coordinate where this node wants to move to |
| vehicle | The vehicle tipe for this route |

[jvm]\
open fun [computeRoute](compute-route.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.md)>, node2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.md)>): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>

This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) calling this method to effectively move nodes along the path. It uses the fastest path as metric.

#### Return

A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md) object describing the path the node should follow

## Parameters

jvm

| | |
|---|---|
| node | The start node |
| node2 | the second node's position will be used as destination |
