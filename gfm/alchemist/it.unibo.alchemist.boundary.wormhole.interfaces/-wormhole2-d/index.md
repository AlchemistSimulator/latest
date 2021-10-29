//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[Wormhole2D](index.md)

# Wormhole2D

[jvm]\
interface [Wormhole2D](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)>?>

A Wormhole (in this context) is an entity that "connects" two worlds: the "environment" and the "view". Above all it provides services to convert coordinates from the "environment-space" to the "view-space". IWormhole2D is the type of a wormhole whose both environment and view are bi-dimensional spaces. Terminology: - "Environment" is the 'rectangle' we need to render ON the view. - "View" is a 'window' that let us see the environment. - "Environment-space" is the algebraic space on which 'lies' the environment. - "View-space" is the algebraic space on which 'lies' the view. - "Env" before a point's name => it refers to a point into the environment-space. - "View" before a point's name => it refers to a point into the view-space. - "Position" is the point of the view-space every transformation applied to the environment refers to: e.g. if I want to move the environment, I have to change the position; it is also the point the environment rotates around. - "EnvOffset" is the vector from (0; 0) into env-space to the left-bottom corner of the part of the environment we want to render. E.g. if I am representing a map with Earth-coordinates (16; 48), the intersection between the prime meridian and the equator is (0; 0), so I have to set the envOffset to (16; 48) in order to see the "beginning" of the map on the left-bottom corner of the view.

## Parameters

jvm

| | |
|---|---|
| <P> | position type |

## Types

| Name | Summary |
|---|---|
| [Mode](-mode/index.md) | [jvm]<br>enum [Mode](-mode/index.md)<br>Wormhole mode. |

## Functions

| Name | Summary |
|---|---|
| [center](center.md) | [jvm]<br>abstract fun [center](center.md)()<br>Points the center of the view on the center of the environment. |
| [getEnvPoint](get-env-point.md) | [jvm]<br>abstract fun [getEnvPoint](get-env-point.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)<br>Converts a point from the view-space to the env-space. |
| [getMode](get-mode.md) | [jvm]<br>abstract fun [getMode](get-mode.md)(): [Wormhole2D.Mode](-mode/index.md)<br>Gets the rendering mode. |
| [getViewPoint](get-view-point.md) | [jvm]<br>abstract fun [getViewPoint](get-view-point.md)(envPoint: [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Converts a point from the env-space to the view-space. |
| [getViewPosition](get-view-position.md) | [jvm]<br>abstract fun [getViewPosition](get-view-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the Position. |
| [getViewSize](get-view-size.md) | [jvm]<br>abstract fun [getViewSize](get-view-size.md)(): [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)<br>Gets the view's size. |
| [getZoom](get-zoom.md) | [jvm]<br>abstract fun [getZoom](get-zoom.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Gets the zoom factor. |
| [isInsideView](is-inside-view.md) | [jvm]<br>abstract fun [isInsideView](is-inside-view.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if a point of the view-space is "visible", i.e. |
| [optimalZoom](optimal-zoom.md) | [jvm]<br>abstract fun [optimalZoom](optimal-zoom.md)()<br>Automatically sets the zoom rate in order to make the environment entirely visible on the view. |
| [rotateAroundPoint](rotate-around-point.md) | [jvm]<br>abstract fun [rotateAroundPoint](rotate-around-point.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), a: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates around a point into the view-space. |
| [setEnvPosition](set-env-position.md) | [jvm]<br>abstract fun [setEnvPosition](set-env-position.md)(envPoint: [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md))<br>Sets the position to the view-point corresponding to envPoint. |
| [setRotation](set-rotation.md) | [jvm]<br>abstract fun [setRotation](set-rotation.md)(rad: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Rotates the environment around the Position. |
| [setViewPosition](set-view-position.md) | [jvm]<br>abstract fun [setViewPosition](set-view-position.md)(viewPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the Position to viewPoint. |
| [setZoom](set-zoom.md) | [jvm]<br>abstract fun [setZoom](set-zoom.md)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Changes the zoom factor. |
| [zoomOnPoint](zoom-on-point.md) | [jvm]<br>abstract fun [zoomOnPoint](zoom-on-point.md)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), z: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>Zooms on a point into the view-space. |

## Inheritors

| Name |
|---|
| [AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md) |
