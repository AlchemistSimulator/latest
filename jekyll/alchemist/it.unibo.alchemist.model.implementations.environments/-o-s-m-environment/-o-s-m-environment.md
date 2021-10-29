---
title: OSMEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[OSMEnvironment](index.html)/[OSMEnvironment](-o-s-m-environment.html)



# OSMEnvironment



[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>)



Builds a new [OSMEnvironment](index.html) without an actual backing map. This environment will be unable to use the navigation system.



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |





[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



Builds a new [OSMEnvironment](index.html), with nodes not forced on streets.



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| file | the file path where the map data is stored |





[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| file | the file path where the map data is stored |
| onStreets | if true, the nodes will be placed on the street nearest to the desired [it.unibo.alchemist.model.interfaces.Position](../../it.unibo.alchemist.model.interfaces/-position/index.html). |





[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), onlyOnStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| file | the file path where the map data is stored |
| onStreets | if true, the nodes will be placed on the street nearest to the desired [it.unibo.alchemist.model.interfaces.Position](../../it.unibo.alchemist.model.interfaces/-position/index.html). |
| onlyOnStreets | if true, the nodes which are too far from a street will be simply discarded. If false, they will be placed anyway, in the original position. |





[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), approximation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| file | the file path where the map data is stored. Accepts OSM maps of any format (xml, osm, pbf). The map will be processed, optimized and stored for future use. |
| approximation | the amount of ciphers of the IEEE 754 encoded position that may be discarded when comparing two positions, allowing a quicker retrieval of the route between two position, since the cache may already contain a similar route which can be considered to be the same route, according to the level of precision determined by this value |





[jvm]\
open fun [OSMEnvironment](-o-s-m-environment.html)(incarnation: [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-straight-line-trace-dependant-speed/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, file: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), approximation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), onStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), onlyOnStreets: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



## Parameters


jvm

| | |
|---|---|
| incarnation | the incarnation to be used. |
| file | the file path where the map data is stored. Accepts OSM maps of any format (xml, osm, pbf). The map will be processed, optimized and stored for future use. |
| approximation | the amount of ciphers of the IEEE 754 encoded position that may be discarded when comparing two positions, allowing a quicker retrieval of the route between two position, since the cache may already contain a similar route which can be considered to be the same route, according to the level of precision determined by this value |
| onStreets | if true, the nodes will be placed on the street nearest to the desired [it.unibo.alchemist.model.interfaces.Position](../../it.unibo.alchemist.model.interfaces/-position/index.html). |
| onlyOnStreets | if true, the nodes which are too far from a street will be simply discarded. If false, they will be placed anyway, in the original position. |




