---
title: WormholeFX
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.wormhole.implementation](../index.html)/[WormholeFX](index.html)



# WormholeFX



[jvm]\
open class [WormholeFX](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, **node**: Node) : [AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.html)<[P](index.html)> 

An implementation of [AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.html) for JavaFX.



## Parameters


jvm

| | |
|---|---|
| P | the type of the position |



## Constructors


| | |
|---|---|
| [WormholeFX](-wormhole-f-x.html) | [jvm]<br>fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>> [WormholeFX](-wormhole-f-x.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)>, node: Node)<br>the type of the position |


## Functions


| Name | Summary |
|---|---|
| [calculateTransform](index.html#-238501275%2FFunctions%2F-134779887) | [jvm]<br>open fun [calculateTransform](index.html#-238501275%2FFunctions%2F-134779887)(): [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html) |
| [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.html) | [jvm]<br>open override fun [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.html)() |
| [envPointFromView](index.html#-1468791767%2FFunctions%2F-134779887) | [jvm]<br>fun [envPointFromView](index.html#-1468791767%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)> |
| [getEnvironment](index.html#172054286%2FFunctions%2F-134779887) | [jvm]<br>fun [getEnvironment](index.html#172054286%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<*, [P](index.html)> |
| [getEnvPoint](index.html#1795398658%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getEnvPoint](index.html#1795398658%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](index.html) |
| [getEnvRatio](index.html#2141438683%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvRatio](index.html#2141438683%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getHRate](index.html#857999449%2FFunctions%2F-134779887) | [jvm]<br>open fun [getHRate](index.html#857999449%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#12876278%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#12876278%2FFunctions%2F-134779887)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html) |
| [getNIHorizontalRatio](index.html#-182384363%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNIHorizontalRatio](index.html#-182384363%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNIVerticalRatio](index.html#-1329451865%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNIVerticalRatio](index.html#-1329451865%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getPosition](index.html#1323425584%2FFunctions%2F-134779887) | [jvm]<br>fun [getPosition](index.html#1323425584%2FFunctions%2F-134779887)(): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)> |
| [getRotation](index.html#1511309947%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRotation](index.html#1511309947%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getView](index.html#709246772%2FFunctions%2F-134779887) | [jvm]<br>fun [getView](index.html#709246772%2FFunctions%2F-134779887)(): [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html) |
| [getViewPoint](index.html#1128621768%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getViewPoint](index.html#1128621768%2FFunctions%2F-134779887)(p0: [P](index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.html) | [jvm]<br>open override fun [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewRatio](index.html#1160341787%2FFunctions%2F-134779887) | [jvm]<br>open fun [getViewRatio](index.html#1160341787%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.html) | [jvm]<br>open override fun [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.html)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getVRate](index.html#1016425227%2FFunctions%2F-134779887) | [jvm]<br>open fun [getVRate](index.html#1016425227%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.html#-1625725498%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](index.html#1329027884%2FFunctions%2F-134779887) | [jvm]<br>open override fun [isInsideView](index.html#1329027884%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/optimal-zoom.html) | [jvm]<br>open override fun [optimalZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/optimal-zoom.html)() |
| [rotateAroundPoint](index.html#829341240%2FFunctions%2F-134779887) | [jvm]<br>open override fun [rotateAroundPoint](index.html#829341240%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](index.html#1198168647%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setEnvPosition](index.html#1198168647%2FFunctions%2F-134779887)(p0: [P](index.html)) |
| [setMode](index.html#2082857849%2FFunctions%2F-134779887) | [jvm]<br>open fun [setMode](index.html#2082857849%2FFunctions%2F-134779887)(p0: [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html)) |
| [setPosition](index.html#-1875252994%2FFunctions%2F-134779887) | [jvm]<br>fun [setPosition](index.html#-1875252994%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)>) |
| [setRotation](index.html#1328566965%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setRotation](index.html#1328566965%2FFunctions%2F-134779887)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](index.html#1615160523%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setViewPosition](index.html#1615160523%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](index.html#-115570870%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setZoom](index.html#-115570870%2FFunctions%2F-134779887)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [viewPointFromEnv](index.html#261960047%2FFunctions%2F-134779887) | [jvm]<br>open fun [viewPointFromEnv](index.html#261960047%2FFunctions%2F-134779887)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.html)<[P](index.html)> |
| [zoomOnPoint](index.html#-1011035838%2FFunctions%2F-134779887) | [jvm]<br>open override fun [zoomOnPoint](index.html#-1011035838%2FFunctions%2F-134779887)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Inheritors


| Name |
|---|
| [LeafletMapWormhole](../-leaflet-map-wormhole/index.html) |

