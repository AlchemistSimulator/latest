//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[MapWormhole](index.md)

# MapWormhole

[jvm]\
class [MapWormhole](index.md) : [WormholeSwing](../-wormhole-swing/index.md)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> 

Wormhole used for maps rendering.

## Constructors

| | |
|---|---|
| [MapWormhole](-map-wormhole.md) | [jvm]<br>open fun [MapWormhole](-map-wormhole.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)>, comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html), m: IMapViewPosition)<br>Initializes a new [MapWormhole](index.md) copying the state of the one in input. |

## Functions

| Name | Summary |
|---|---|
| [center](../-abstract-wormhole2-d/center.md) | [jvm]<br>open fun [center](../-abstract-wormhole2-d/center.md)() |
| [getEnvPoint](get-env-point.md) | [jvm]<br>open fun [getEnvPoint](get-env-point.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [getMode](index.md#12876278%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMode](index.md#12876278%2FFunctions%2F-267951372)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.md) |
| [getViewPoint](get-view-point.md) | [jvm]<br>open fun [getViewPoint](get-view-point.md)(environmentPoint: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](get-view-position.md) | [jvm]<br>open fun [getViewPosition](get-view-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewSize](../-abstract-wormhole2-d/get-view-size.md) | [jvm]<br>open fun [getViewSize](../-abstract-wormhole2-d/get-view-size.md)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getZoom](index.md#-1625725498%2FFunctions%2F-267951372) | [jvm]<br>open fun [getZoom](index.md#-1625725498%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](../-abstract-wormhole2-d/is-inside-view.md) | [jvm]<br>open fun [isInsideView](../-abstract-wormhole2-d/is-inside-view.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](optimal-zoom.md) | [jvm]<br>open fun [optimalZoom](optimal-zoom.md)() |
| [rotateAroundPoint](rotate-around-point.md) | [jvm]<br>open fun [rotateAroundPoint](rotate-around-point.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](set-env-position.md) | [jvm]<br>open fun [setEnvPosition](set-env-position.md)(ep: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)) |
| [setRotation](index.md#-365162114%2FFunctions%2F-267951372) | [jvm]<br>open fun [setRotation](index.md#-365162114%2FFunctions%2F-267951372)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](set-view-position.md) | [jvm]<br>open fun [setViewPosition](set-view-position.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](set-zoom.md) | [jvm]<br>open fun [setZoom](set-zoom.md)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [zoomOnPoint](zoom-on-point.md) | [jvm]<br>open fun [zoomOnPoint](zoom-on-point.md)(zoomPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [MAX_ZOOM](-m-a-x_-z-o-o-m.md) | [jvm]<br>val [MAX_ZOOM](-m-a-x_-z-o-o-m.md): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>Maximum zoom. |
