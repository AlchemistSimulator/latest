---
title: it.unibo.alchemist.wormhole.implementation
---
//[alchemist](../../index.html)/[it.unibo.alchemist.wormhole.implementation](index.html)



# Package it.unibo.alchemist.wormhole.implementation



## Types


| Name | Summary |
|---|---|
| [LeafletMapWormhole](-leaflet-map-wormhole/index.html) | [jvm]<br>class [LeafletMapWormhole](-leaflet-map-wormhole/index.html)(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, **node**: Node, **map**: [CustomLeafletMapView](../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.html)) : [WormholeFX](-wormhole-f-x/index.html)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>The wormhole used for managing a [CustomLeafletMapView](../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.html). |
| [WormholeFX](-wormhole-f-x/index.html) | [jvm]<br>open class [WormholeFX](-wormhole-f-x/index.html)<[P](-wormhole-f-x/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-wormhole-f-x/index.html)>>(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](-wormhole-f-x/index.html)>, **node**: Node) : [AbstractWormhole2D](../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.html)<[P](-wormhole-f-x/index.html)> <br>An implementation of [AbstractWormhole2D](../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.html) for JavaFX. |


## Functions


| Name | Summary |
|---|---|
| [toGeoPosition](to-geo-position.html) | [jvm]<br>fun LatLong.[toGeoPosition](to-geo-position.html)(): [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>Converts this to [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html). |
| [toLatLong](to-lat-long.html) | [jvm]<br>fun [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html).[toLatLong](to-lat-long.html)(): LatLong<br>Converts [this](../it.unibo.alchemist.model.interfaces/-geo-position/index.html) to LatLong. |

