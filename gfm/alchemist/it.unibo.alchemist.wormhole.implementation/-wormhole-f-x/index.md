//[alchemist](../../../index.md)/[it.unibo.alchemist.wormhole.implementation](../index.md)/[WormholeFX](index.md)

# WormholeFX

[jvm]\
open class [WormholeFX](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, **node**: Node) : [AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)<[P](index.md)> 

An implementation of [AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md) for JavaFX.

## Parameters

jvm

| | |
|---|---|
| P | the type of the position |

## Constructors

| | |
|---|---|
| [WormholeFX](-wormhole-f-x.md) | [jvm]<br>fun <[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>> [WormholeFX](-wormhole-f-x.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)>, node: Node)<br>the type of the position |

## Functions

| Name | Summary |
|---|---|
| [calculateTransform](index.md#-238501275%2FFunctions%2F-267951372) | [jvm]<br>open fun [calculateTransform](index.md#-238501275%2FFunctions%2F-267951372)(): [AffineTransform](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/AffineTransform.html) |
| [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.md) | [jvm]<br>open override fun [center](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/center.md)() |
| [envPointFromView](index.md#-1468791767%2FFunctions%2F-267951372) | [jvm]<br>fun [envPointFromView](index.md#-1468791767%2FFunctions%2F-267951372)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)> |
| [getEnvironment](index.md#172054286%2FFunctions%2F-267951372) | [jvm]<br>fun [getEnvironment](index.md#172054286%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<*, [P](index.md)> |
| [getEnvPoint](index.md#1795398658%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getEnvPoint](index.md#1795398658%2FFunctions%2F-267951372)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](index.md) |
| [getEnvRatio](index.md#2141438683%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvRatio](index.md#2141438683%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getHRate](index.md#857999449%2FFunctions%2F-267951372) | [jvm]<br>open fun [getHRate](index.md#857999449%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.md#12876278%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getMode](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.md#12876278%2FFunctions%2F-267951372)(): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.md) |
| [getNIHorizontalRatio](index.md#-182384363%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNIHorizontalRatio](index.md#-182384363%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNIVerticalRatio](index.md#-1329451865%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNIVerticalRatio](index.md#-1329451865%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getPosition](index.md#1323425584%2FFunctions%2F-267951372) | [jvm]<br>fun [getPosition](index.md#1323425584%2FFunctions%2F-267951372)(): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)> |
| [getRotation](index.md#1511309947%2FFunctions%2F-267951372) | [jvm]<br>open fun [getRotation](index.md#1511309947%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getView](index.md#709246772%2FFunctions%2F-267951372) | [jvm]<br>fun [getView](index.md#709246772%2FFunctions%2F-267951372)(): [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md) |
| [getViewPoint](index.md#1128621768%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getViewPoint](index.md#1128621768%2FFunctions%2F-267951372)(p0: [P](index.md)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.md) | [jvm]<br>open override fun [getViewPosition](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getViewRatio](index.md#1160341787%2FFunctions%2F-267951372) | [jvm]<br>open fun [getViewRatio](index.md#1160341787%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.md) | [jvm]<br>open override fun [getViewSize](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/get-view-size.md)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) |
| [getVRate](index.md#1016425227%2FFunctions%2F-267951372) | [jvm]<br>open fun [getVRate](index.md#1016425227%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.md#-1625725498%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-map-wormhole/index.md#-1625725498%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isInsideView](index.md#1329027884%2FFunctions%2F-267951372) | [jvm]<br>open override fun [isInsideView](index.md#1329027884%2FFunctions%2F-267951372)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [optimalZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/optimal-zoom.md) | [jvm]<br>open override fun [optimalZoom](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/optimal-zoom.md)() |
| [rotateAroundPoint](index.md#829341240%2FFunctions%2F-267951372) | [jvm]<br>open override fun [rotateAroundPoint](index.md#829341240%2FFunctions%2F-267951372)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setEnvPosition](index.md#1198168647%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setEnvPosition](index.md#1198168647%2FFunctions%2F-267951372)(p0: [P](index.md)) |
| [setMode](index.md#2082857849%2FFunctions%2F-267951372) | [jvm]<br>open fun [setMode](index.md#2082857849%2FFunctions%2F-267951372)(p0: [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.md)) |
| [setPosition](index.md#-1875252994%2FFunctions%2F-267951372) | [jvm]<br>fun [setPosition](index.md#-1875252994%2FFunctions%2F-267951372)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)>) |
| [setRotation](index.md#1328566965%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setRotation](index.md#1328566965%2FFunctions%2F-267951372)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setViewPosition](index.md#1615160523%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setViewPosition](index.md#1615160523%2FFunctions%2F-267951372)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [setZoom](index.md#-115570870%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setZoom](index.md#-115570870%2FFunctions%2F-267951372)(p0: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [viewPointFromEnv](index.md#261960047%2FFunctions%2F-267951372) | [jvm]<br>open fun [viewPointFromEnv](index.md#261960047%2FFunctions%2F-267951372)(p0: [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)>): [PointAdapter](../../it.unibo.alchemist.boundary.wormhole.implementation/-point-adapter/index.md)<[P](index.md)> |
| [zoomOnPoint](index.md#-1011035838%2FFunctions%2F-267951372) | [jvm]<br>open override fun [zoomOnPoint](index.md#-1011035838%2FFunctions%2F-267951372)(p0: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p1: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Inheritors

| Name |
|---|
| [LeafletMapWormhole](../-leaflet-map-wormhole/index.md) |
