//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[WormholeSwing](index.md)

# WormholeSwing

[jvm]\
open class [WormholeSwing](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> : [AbstractWormhole2D](../-abstract-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)> 

An implementation of [AbstractWormhole2D] for Swing.

## Parameters

jvm

| | |
|---|---|
| <P> | the type of the position |

## Constructors

| | |
|---|---|
| [WormholeSwing](-wormhole-swing.md) | [jvm]<br>open fun [WormholeSwing](-wormhole-swing.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, component: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |

## Functions

| Name | Summary |
|---|---|
| [center](../-abstract-wormhole2-d/center.md) | [jvm]<br>open fun [center](../-abstract-wormhole2-d/center.md)() |
| [getEnvPoint](../-abstract-wormhole2-d/get-env-point.md) | [jvm]<br>open fun [getEnvPoint](../-abstract-wormhole2-d/get-env-point.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md) |
| [getMode](../-map-wormhole/index.md#12876278%2FFunctions%2F-267951372) | [jvm]<br>open fun [getMode](../-map-wormhole/index.md#12876278%2FFunctions%2F-267951372)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.md) |
| [getViewPoint](../-abstract-wormhole2-d/get-view-point.md) | [jvm]<br>open fun [getViewPoint](../-abstract-wormhole2-d/get-view-point.md)(envPoint: [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](../-abstract-wormhole2-d/get-view-position.md) | [jvm]<br>open fun [getViewPosition](../-abstract-wormhole2-d/get-view-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewSize](../-abstract-wormhole2-d/get-view-size.md) | [jvm]<br>open fun [getViewSize](../-abstract-wormhole2-d/get-view-size.md)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getZoom](../-map-wormhole/index.md#-1625725498%2FFunctions%2F-267951372) | [jvm]<br>open fun [getZoom](../-map-wormhole/index.md#-1625725498%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](../-abstract-wormhole2-d/is-inside-view.md) | [jvm]<br>open fun [isInsideView](../-abstract-wormhole2-d/is-inside-view.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](../-abstract-wormhole2-d/optimal-zoom.md) | [jvm]<br>open fun [optimalZoom](../-abstract-wormhole2-d/optimal-zoom.md)() |
| [rotateAroundPoint](../-abstract-wormhole2-d/rotate-around-point.md) | [jvm]<br>open fun [rotateAroundPoint](../-abstract-wormhole2-d/rotate-around-point.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](../-abstract-wormhole2-d/set-env-position.md) | [jvm]<br>open fun [setEnvPosition](../-abstract-wormhole2-d/set-env-position.md)(envPoint: [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)) |
| [setRotation](../-map-wormhole/index.md#-365162114%2FFunctions%2F-267951372) | [jvm]<br>open fun [setRotation](../-map-wormhole/index.md#-365162114%2FFunctions%2F-267951372)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](../-abstract-wormhole2-d/set-view-position.md) | [jvm]<br>open fun [setViewPosition](../-abstract-wormhole2-d/set-view-position.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](index.md#-1433490807%2FFunctions%2F-267951372) | [jvm]<br>open fun [setZoom](index.md#-1433490807%2FFunctions%2F-267951372)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [zoomOnPoint](../-abstract-wormhole2-d/zoom-on-point.md) | [jvm]<br>open fun [zoomOnPoint](../-abstract-wormhole2-d/zoom-on-point.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), zoomRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Inheritors

| Name |
|---|
| [MapWormhole](../-map-wormhole/index.md) |
