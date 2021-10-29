---
title: AbstractWormhole2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[AbstractWormhole2D](index.html)



# AbstractWormhole2D



[jvm]\
abstract class [AbstractWormhole2D](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../-point-adapter/index.html)>?> : [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../-point-adapter/index.html)> 

Partial, abstract, implementation for the interface [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html). This implementation considers the particular case of the view as an entity into the sceern-space: the y-axis grows on the bottom side of the screen. This abstract class is independent from the 2D graphical component wrapped.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Constructors


| | |
|---|---|
| [AbstractWormhole2D](-abstract-wormhole2-d.html) | [jvm]<br>open fun <[T](-abstract-wormhole2-d.html) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html)?> [AbstractWormhole2D](-abstract-wormhole2-d.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../-point-adapter/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()view: [T](-abstract-wormhole2-d.html), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()viewTypeToPointAdapter: ([T](-abstract-wormhole2-d.html)) -> [PointAdapter](../-point-adapter/index.html)<[P](../-point-adapter/index.html)>)<br>Wormhole constructor for any [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html). |


## Functions


| Name | Summary |
|---|---|
| [center](center.html) | [jvm]<br>open fun [center](center.html)()<br>Points the center of the view on the center of the environment. |
| [getEnvPoint](get-env-point.html) | [jvm]<br>open fun [getEnvPoint](get-env-point.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](../-point-adapter/index.html)<br>Converts a point from the view-space to the env-space. |
| [getViewPoint](get-view-point.html) | [jvm]<br>open fun [getViewPoint](get-view-point.html)(envPoint: [P](../-point-adapter/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Converts a point from the env-space to the view-space. |
| [getViewPosition](get-view-position.html) | [jvm]<br>open fun [getViewPosition](get-view-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the Position. |
| [getViewSize](get-view-size.html) | [jvm]<br>open fun [getViewSize](get-view-size.html)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)<br>Gets the view's size. |
| [isInsideView](is-inside-view.html) | [jvm]<br>open fun [isInsideView](is-inside-view.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if a point of the view-space is "visible", i.e. |
| [optimalZoom](optimal-zoom.html) | [jvm]<br>open fun [optimalZoom](optimal-zoom.html)()<br>Automatically sets the zoom rate in order to make the environment entirely visible on the view. |
| [rotateAroundPoint](rotate-around-point.html) | [jvm]<br>open fun [rotateAroundPoint](rotate-around-point.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates around a point into the view-space. |
| [setEnvPosition](set-env-position.html) | [jvm]<br>open fun [setEnvPosition](set-env-position.html)(envPoint: [P](../-point-adapter/index.html))<br>Sets the position to the view-point corresponding to envPoint. |
| [setRotation](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-rotation.html) | [jvm]<br>abstract fun [setRotation](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-rotation.html)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates the environment around the Position. |
| [setViewPosition](set-view-position.html) | [jvm]<br>open fun [setViewPosition](set-view-position.html)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the Position to viewPoint. |
| [setZoom](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-zoom.html) | [jvm]<br>abstract fun [setZoom](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/set-zoom.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Changes the zoom factor. |
| [zoomOnPoint](zoom-on-point.html) | [jvm]<br>open fun [zoomOnPoint](zoom-on-point.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), zoomRate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Zooms on a point into the view-space. |


## Properties


| Name | Summary |
|---|---|
| [mode](mode.html) | [jvm]<br>private open var [mode](mode.html): [Wormhole2D.Mode](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/-mode/index.html) |
| [rotation](rotation.html) | [jvm]<br>private open var [rotation](rotation.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [zoom](zoom.html) | [jvm]<br>private open var [zoom](zoom.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [WormholeFX](../../it.unibo.alchemist.wormhole.implementation/-wormhole-f-x/index.html) |
| [WormholeSwing](../-wormhole-swing/index.html) |

