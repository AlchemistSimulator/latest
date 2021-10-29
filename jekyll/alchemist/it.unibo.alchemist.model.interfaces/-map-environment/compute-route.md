---
title: computeRoute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[MapEnvironment](index.html)/[computeRoute](compute-route.html)



# computeRoute



[jvm]\
abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-reproduce-g-p-s-trace/index.html)>, node2: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-reproduce-g-p-s-trace/index.html)>): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.html) calling this method to effectively move nodes along the path. It uses the fastest path as metric.



#### Return



A [Route](../-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The start node |
| node2 | the second node's position will be used as destination |





[jvm]\
abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-reproduce-g-p-s-trace/index.html)>, coord: [GeoPosition](../-geo-position/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The [Node](../-node/index.html) to move |
| coord | The absolute coordinate where this node wants to move to |





[jvm]\
abstract fun [computeRoute](compute-route.html)(node: [Node](../-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.actions/-reproduce-g-p-s-trace/index.html)>, coord: [GeoPosition](../-geo-position/index.html), vehicle: [Vehicle](../-vehicle/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The [Node](../-node/index.html) to move |
| coord | The absolute coordinate where this node wants to move to |
| vehicle | The vehicle tipe for this route |





[jvm]\
abstract fun [computeRoute](compute-route.html)(p1: [GeoPosition](../-geo-position/index.html), p2: [GeoPosition](../-geo-position/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |





[jvm]\
abstract fun [computeRoute](compute-route.html)(p1: [GeoPosition](../-geo-position/index.html), p2: [GeoPosition](../-geo-position/index.html), vehicle: [Vehicle](../-vehicle/index.html)): [Route](../-route/index.html)<[GeoPosition](../-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |
| vehicle | vehicle to use. Different vehicles may use different paths, e.g. pedestrians can't go along a highway, but can walk the parks |




