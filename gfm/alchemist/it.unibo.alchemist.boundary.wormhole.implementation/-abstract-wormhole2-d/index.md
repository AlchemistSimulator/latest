//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[AbstractWormhole2D](index.md)

# AbstractWormhole2D

[jvm]\
abstract class [AbstractWormhole2D](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)>?> : [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)> 

Partial, abstract, implementation for the interface [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md). This implementation considers the particular case of the view as an entity into the sceern-space: the y-axis grows on the bottom side of the screen. This abstract class is independent from the 2D graphical component wrapped.

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |

## Constructors

| | |
|---|---|
| [AbstractWormhole2D](-abstract-wormhole2-d.md) | [jvm]<br>open fun <[T](-abstract-wormhole2-d.md) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md)?> [AbstractWormhole2D](-abstract-wormhole2-d.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()view: [T](-abstract-wormhole2-d.md), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()viewTypeToPointAdapter: ([T](-abstract-wormhole2-d.md)) -> [PointAdapter](../-point-adapter/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)>)<br>Wormhole constructor for any [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md). |

## Functions

| Name | Summary |
|---|---|
| [center](center.md) | [jvm]<br>open fun [center](center.md)()<br>Points the center of the view on the center of the environment. |
| [getEnvPoint](get-env-point.md) | [jvm]<br>open fun [getEnvPoint](get-env-point.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<br>Converts a point from the view-space to the env-space. |
| [getViewPoint](get-view-point.md) | [jvm]<br>open fun [getViewPoint](get-view-point.md)(envPoint: [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Converts a point from the env-space to the view-space. |
| [getViewPosition](get-view-position.md) | [jvm]<br>open fun [getViewPosition](get-view-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the Position. |
| [getViewSize](get-view-size.md) | [jvm]<br>open fun [getViewSize](get-view-size.md)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)<br>Gets the view's size. |
| [isInsideView](is-inside-view.md) | [jvm]<br>open fun [isInsideView](is-inside-view.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if a point of the view-space is "visible", i.e. |
| [optimalZoom](optimal-zoom.md) | [jvm]<br>open fun [optimalZoom](optimal-zoom.md)()<br>Automatically sets the zoom rate in order to make the environment entirely visible on the view. |
| [rotateAroundPoint](rotate-around-point.md) | [jvm]<br>open fun [rotateAroundPoint](rotate-around-point.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates around a point into the view-space. |
| [setEnvPosition](set-env-position.md) | [jvm]<br>open fun [setEnvPosition](set-env-position.md)(envPoint: [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md))<br>Sets the position to the view-point corresponding to envPoint. |
| [setRotation](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-rotation.md) | [jvm]<br>abstract fun [setRotation](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-rotation.md)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates the environment around the Position. |
| [setViewPosition](set-view-position.md) | [jvm]<br>open fun [setViewPosition](set-view-position.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the Position to viewPoint. |
| [setZoom](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-zoom.md) | [jvm]<br>abstract fun [setZoom](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-zoom.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Changes the zoom factor. |
| [zoomOnPoint](zoom-on-point.md) | [jvm]<br>open fun [zoomOnPoint](zoom-on-point.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), zoomRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Zooms on a point into the view-space. |

## Properties

| Name | Summary |
|---|---|
| [mode](mode.md) | [jvm]<br>private open var [mode](mode.md): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.md) |
| [rotation](rotation.md) | [jvm]<br>private open var [rotation](rotation.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [zoom](zoom.md) | [jvm]<br>private open var [zoom](zoom.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [WormholeFX](../../it.unibo.alchemist.wormhole.implementation/-wormhole-f-x/index.md) |
| [WormholeSwing](../-wormhole-swing/index.md) |
