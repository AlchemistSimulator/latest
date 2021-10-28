---
title: LeafletMapWormhole
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.wormhole.implementation](../index.html)/[LeafletMapWormhole](index.html)



# LeafletMapWormhole



[jvm]\
class [LeafletMapWormhole](index.html)(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, **node**: Node, **map**: [CustomLeafletMapView](../../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.html)) : [WormholeFX](../-wormhole-f-x/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

The wormhole used for managing a [CustomLeafletMapView](../../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.html).



## Constructors


| | |
|---|---|
| [LeafletMapWormhole](-leaflet-map-wormhole.html) | [jvm]<br>fun [LeafletMapWormhole](-leaflet-map-wormhole.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, node: Node, map: [CustomLeafletMapView](../../it.unibo.alchemist.boundary/-custom-leaflet-map-view/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [calculateTransform](../-wormhole-f-x/index.html#-238501275%2FFunctions%2F-134779887) | [jvm]<br>open fun [calculateTransform](../-wormhole-f-x/index.html#-238501275%2FFunctions%2F-134779887)(): [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html) |
| [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.html) | [jvm]<br>open override fun [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.html)() |
| [envPointFromView](index.html#373615232%2FFunctions%2F-134779887) | [jvm]<br>fun [envPointFromView](index.html#373615232%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [getEnvironment](../-wormhole-f-x/index.html#172054286%2FFunctions%2F-134779887) | [jvm]<br>fun [getEnvironment](../-wormhole-f-x/index.html#172054286%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [getEnvPoint](get-env-point.html) | [jvm]<br>open override fun [getEnvPoint](get-env-point.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [getEnvRatio](../-wormhole-f-x/index.html#2141438683%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvRatio](../-wormhole-f-x/index.html#2141438683%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getHRate](../-wormhole-f-x/index.html#857999449%2FFunctions%2F-134779887) | [jvm]<br>open fun [getHRate](../-wormhole-f-x/index.html#857999449%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#12876278%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#12876278%2FFunctions%2F-134779887)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html) |
| [getNIHorizontalRatio](../-wormhole-f-x/index.html#-182384363%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNIHorizontalRatio](../-wormhole-f-x/index.html#-182384363%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNIVerticalRatio](../-wormhole-f-x/index.html#-1329451865%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNIVerticalRatio](../-wormhole-f-x/index.html#-1329451865%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getPosition](../-wormhole-f-x/index.html#1323425584%2FFunctions%2F-134779887) | [jvm]<br>fun [getPosition](../-wormhole-f-x/index.html#1323425584%2FFunctions%2F-134779887)(): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [getRotation](../-wormhole-f-x/index.html#1511309947%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRotation](../-wormhole-f-x/index.html#1511309947%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getView](../-wormhole-f-x/index.html#709246772%2FFunctions%2F-134779887) | [jvm]<br>fun [getView](../-wormhole-f-x/index.html#709246772%2FFunctions%2F-134779887)(): [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html) |
| [getViewPoint](get-view-point.html) | [jvm]<br>open override fun [getViewPoint](get-view-point.html)(envPoint: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.html) | [jvm]<br>open override fun [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewRatio](../-wormhole-f-x/index.html#1160341787%2FFunctions%2F-134779887) | [jvm]<br>open fun [getViewRatio](../-wormhole-f-x/index.html#1160341787%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.html) | [jvm]<br>open override fun [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.html)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getVRate](../-wormhole-f-x/index.html#1016425227%2FFunctions%2F-134779887) | [jvm]<br>open fun [getVRate](../-wormhole-f-x/index.html#1016425227%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](../-wormhole-f-x/index.html#1329027884%2FFunctions%2F-134779887) | [jvm]<br>open override fun [isInsideView](../-wormhole-f-x/index.html#1329027884%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](optimal-zoom.html) | [jvm]<br>open override fun [optimalZoom](optimal-zoom.html)() |
| [rotateAroundPoint](rotate-around-point.html) | [jvm]<br>open override fun [rotateAroundPoint](rotate-around-point.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)?, a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html) |
| [setEnvPosition](set-env-position.html) | [jvm]<br>open override fun [setEnvPosition](set-env-position.html)(envPoint: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)) |
| [setMode](../-wormhole-f-x/index.html#2082857849%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMode](../-wormhole-f-x/index.html#2082857849%2FFunctions%2F-134779887)(p0: [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html)) |
| [setPosition](index.html#536747285%2FFunctions%2F-134779887) | [jvm]<br>fun [setPosition](index.html#536747285%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>) |
| [setRotation](../-wormhole-f-x/index.html#1328566965%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setRotation](../-wormhole-f-x/index.html#1328566965%2FFunctions%2F-134779887)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](set-view-position.html) | [jvm]<br>open override fun [setViewPosition](set-view-position.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](set-zoom.html) | [jvm]<br>open override fun [setZoom](set-zoom.html)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [viewPointFromEnv](index.html#-1373941690%2FFunctions%2F-134779887) | [jvm]<br>open fun [viewPointFromEnv](index.html#-1373941690%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [zoomOnPoint](zoom-on-point.html) | [jvm]<br>open override fun [zoomOnPoint](zoom-on-point.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), zoomRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

