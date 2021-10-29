---
title: computeRoute
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[OSMEnvironment](index.html)/[computeRoute](compute-route.html)



# computeRoute



[jvm]\
open fun [computeRoute](compute-route.html)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |





[jvm]\
open fun [computeRoute](compute-route.html)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| p1 | start position |
| p2 | end position The absolute coordinate where this node wants to move to |
| vehicle | vehicle to use. Different vehicles may use different paths, e.g. pedestrians can't go along a highway, but can walk the parks |





[jvm]\
open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.html)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) to move |
| coord | The absolute coordinate where this node wants to move to |





[jvm]\
open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.html)>, coord: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), vehicle: [Vehicle](../../it.unibo.alchemist.model.interfaces/-vehicle/index.html)): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) calling this method to effectively move nodes along the path.



#### Return



A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) to move |
| coord | The absolute coordinate where this node wants to move to |
| vehicle | The vehicle tipe for this route |





[jvm]\
open fun [computeRoute](compute-route.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.html)>, node2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-trace-dependant-speed/index.html)>): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>



This method relies on the map data, and computes a route towards some absolute coordinate solving a TSP problem. It's up to the specific [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) calling this method to effectively move nodes along the path. It uses the fastest path as metric.



#### Return



A [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html) object describing the path the node should follow



## Parameters


jvm

| | |
|---|---|
| node | The start node |
| node2 | the second node's position will be used as destination |




