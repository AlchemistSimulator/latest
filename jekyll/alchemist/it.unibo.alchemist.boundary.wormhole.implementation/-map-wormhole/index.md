---
title: MapWormhole
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[MapWormhole](index.html)



# MapWormhole



[jvm]\
class [MapWormhole](index.html) : [WormholeSwing](../-wormhole-swing/index.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> 

Wormhole used for maps rendering.



## Constructors


| | |
|---|---|
| [MapWormhole](-map-wormhole.html) | [jvm]<br>open fun [MapWormhole](-map-wormhole.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)>, comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html), m: IMapViewPosition)<br>Initializes a new [MapWormhole](index.html) copying the state of the one in input. |


## Functions


| Name | Summary |
|---|---|
| [center](../-abstract-wormhole2-d/center.html) | [jvm]<br>open fun [center](../-abstract-wormhole2-d/center.html)() |
| [getEnvPoint](get-env-point.html) | [jvm]<br>open fun [getEnvPoint](get-env-point.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [getMode](index.html#12876278%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMode](index.html#12876278%2FFunctions%2F-134779887)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html) |
| [getViewPoint](get-view-point.html) | [jvm]<br>open fun [getViewPoint](get-view-point.html)(environmentPoint: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](get-view-position.html) | [jvm]<br>open fun [getViewPosition](get-view-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewSize](../-abstract-wormhole2-d/get-view-size.html) | [jvm]<br>open fun [getViewSize](../-abstract-wormhole2-d/get-view-size.html)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getZoom](index.html#-1625725498%2FFunctions%2F-134779887) | [jvm]<br>open fun [getZoom](index.html#-1625725498%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](../-abstract-wormhole2-d/is-inside-view.html) | [jvm]<br>open fun [isInsideView](../-abstract-wormhole2-d/is-inside-view.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](optimal-zoom.html) | [jvm]<br>open fun [optimalZoom](optimal-zoom.html)() |
| [rotateAroundPoint](rotate-around-point.html) | [jvm]<br>open fun [rotateAroundPoint](rotate-around-point.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](set-env-position.html) | [jvm]<br>open fun [setEnvPosition](set-env-position.html)(ep: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)) |
| [setRotation](index.html#-365162114%2FFunctions%2F-134779887) | [jvm]<br>open fun [setRotation](index.html#-365162114%2FFunctions%2F-134779887)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](set-view-position.html) | [jvm]<br>open fun [setViewPosition](set-view-position.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](set-zoom.html) | [jvm]<br>open fun [setZoom](set-zoom.html)(z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [zoomOnPoint](zoom-on-point.html) | [jvm]<br>open fun [zoomOnPoint](zoom-on-point.html)(zoomPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [MAX_ZOOM](-m-a-x_-z-o-o-m.html) | [jvm]<br>val [MAX_ZOOM](-m-a-x_-z-o-o-m.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>Maximum zoom. |

