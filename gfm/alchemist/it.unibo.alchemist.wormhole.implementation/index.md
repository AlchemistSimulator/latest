//[alchemist](../../index.md)/[it.unibo.alchemist.wormhole.implementation](index.md)

# Package it.unibo.alchemist.wormhole.implementation

## Types

| Name | Summary |
|---|---|
| [LeafletMapWormhole](-leaflet-map-wormhole/index.md) | [jvm]<br>class [LeafletMapWormhole](-leaflet-map-wormhole/index.md)(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, **node**: Node, **map**: [CustomLeafletMapView](../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.md)) : [WormholeFX](-wormhole-f-x/index.md)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> <br>The wormhole used for managing a [CustomLeafletMapView](../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.md). |
| [WormholeFX](-wormhole-f-x/index.md) | [jvm]<br>open class [WormholeFX](-wormhole-f-x/index.md)<[P](-wormhole-f-x/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](-wormhole-f-x/index.md)>>(**environment**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](-wormhole-f-x/index.md)>, **node**: Node) : [AbstractWormhole2D](../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)<[P](-wormhole-f-x/index.md)> <br>An implementation of [AbstractWormhole2D](../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md) for JavaFX. |

## Functions

| Name | Summary |
|---|---|
| [toGeoPosition](to-geo-position.md) | [jvm]<br>fun LatLong.[toGeoPosition](to-geo-position.md)(): [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>Converts this to [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md). |
| [toLatLong](to-lat-long.md) | [jvm]<br>fun [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md).[toLatLong](to-lat-long.md)(): LatLong<br>Converts [this](../it.unibo.alchemist.model.interfaces/-geo-position/index.md) to LatLong. |
