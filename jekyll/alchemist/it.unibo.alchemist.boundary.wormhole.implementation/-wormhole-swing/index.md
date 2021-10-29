---
title: WormholeSwing
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[WormholeSwing](index.html)



# WormholeSwing



[jvm]\
open class [WormholeSwing](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>?> : [AbstractWormhole2D](../-abstract-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)> 

An implementation of [AbstractWormhole2D] for Swing.



## Parameters


jvm

| | |
|---|---|
| <P> | the type of the position |



## Constructors


| | |
|---|---|
| [WormholeSwing](-wormhole-swing.html) | [jvm]<br>open fun [WormholeSwing](-wormhole-swing.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, component: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |


## Functions


| Name | Summary |
|---|---|
| [center](../-abstract-wormhole2-d/center.html) | [jvm]<br>open fun [center](../-abstract-wormhole2-d/center.html)() |
| [getEnvPoint](../-abstract-wormhole2-d/get-env-point.html) | [jvm]<br>open fun [getEnvPoint](../-abstract-wormhole2-d/get-env-point.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html) |
| [getMode](../-map-wormhole/index.html#12876278%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMode](../-map-wormhole/index.html#12876278%2FFunctions%2F-134779887)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html) |
| [getViewPoint](../-abstract-wormhole2-d/get-view-point.html) | [jvm]<br>open fun [getViewPoint](../-abstract-wormhole2-d/get-view-point.html)(envPoint: [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](../-abstract-wormhole2-d/get-view-position.html) | [jvm]<br>open fun [getViewPosition](../-abstract-wormhole2-d/get-view-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewSize](../-abstract-wormhole2-d/get-view-size.html) | [jvm]<br>open fun [getViewSize](../-abstract-wormhole2-d/get-view-size.html)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getZoom](../-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887) | [jvm]<br>open fun [getZoom](../-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](../-abstract-wormhole2-d/is-inside-view.html) | [jvm]<br>open fun [isInsideView](../-abstract-wormhole2-d/is-inside-view.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](../-abstract-wormhole2-d/optimal-zoom.html) | [jvm]<br>open fun [optimalZoom](../-abstract-wormhole2-d/optimal-zoom.html)() |
| [rotateAroundPoint](../-abstract-wormhole2-d/rotate-around-point.html) | [jvm]<br>open fun [rotateAroundPoint](../-abstract-wormhole2-d/rotate-around-point.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](../-abstract-wormhole2-d/set-env-position.html) | [jvm]<br>open fun [setEnvPosition](../-abstract-wormhole2-d/set-env-position.html)(envPoint: [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)) |
| [setRotation](../-map-wormhole/index.html#-365162114%2FFunctions%2F-134779887) | [jvm]<br>open fun [setRotation](../-map-wormhole/index.html#-365162114%2FFunctions%2F-134779887)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](../-abstract-wormhole2-d/set-view-position.html) | [jvm]<br>open fun [setViewPosition](../-abstract-wormhole2-d/set-view-position.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](index.html#-1433490807%2FFunctions%2F-134779887) | [jvm]<br>open fun [setZoom](index.html#-1433490807%2FFunctions%2F-134779887)(zoom: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [zoomOnPoint](../-abstract-wormhole2-d/zoom-on-point.html) | [jvm]<br>open fun [zoomOnPoint](../-abstract-wormhole2-d/zoom-on-point.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), zoomRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Inheritors


| Name |
|---|
| [MapWormhole](../-map-wormhole/index.html) |

