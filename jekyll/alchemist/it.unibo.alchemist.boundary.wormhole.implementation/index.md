---
title: it.unibo.alchemist.boundary.wormhole.implementation
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](index.html)



# Package it.unibo.alchemist.boundary.wormhole.implementation



## Types


| Name | Summary |
|---|---|
| [AbstractSlideInputManager](-abstract-slide-input-manager/index.html) | [jvm]<br>open class [AbstractSlideInputManager](-abstract-slide-input-manager/index.html) : [SlideInputManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/index.html)<br>ASlideInputManager is the base class for any class whose aim is to handle the the sliding of any physical/virtual device/control. |
| [AbstractWormhole2D](-abstract-wormhole2-d/index.html) | [jvm]<br>abstract class [AbstractWormhole2D](-abstract-wormhole2-d/index.html)<[P](-abstract-wormhole2-d/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> : [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)> <br>Partial, abstract, implementation for the interface [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html). |
| [AngleManagerImpl](-angle-manager-impl/index.html) | [jvm]<br>class [AngleManagerImpl](-angle-manager-impl/index.html) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.html), [AngleManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-angle-manager/index.html)<br>An AngleManager converts the sliding of any physical/virtual device/control into an angle expressed with radians. |
| [DoubleDimension](-double-dimension/index.html) | [jvm]<br>class [DoubleDimension](-double-dimension/index.html) : [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)<br>Implementation of the [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) abstract class with double precision. |
| [ExponentialZoomManager](-exponential-zoom-manager/index.html) | [jvm]<br>class [ExponentialZoomManager](-exponential-zoom-manager/index.html) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.html), [ZoomManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html)<br>An ExpZoomManager converts the sliding of any physical/virtual device/control into a zoom rate through an exponential function (in this way I am sure to not see negative values ;-). |
| [LinearZoomManager](-linear-zoom-manager/index.html) | [jvm]<br>class [LinearZoomManager](-linear-zoom-manager/index.html) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.html), [ZoomManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.html)<br>A [LinearZoomManager](-linear-zoom-manager/index.html) converts the sliding of any physical/virtual device/control into a zoom rate through a linear function. |
| [MapWormhole](-map-wormhole/index.html) | [jvm]<br>class [MapWormhole](-map-wormhole/index.html) : [WormholeSwing](-wormhole-swing/index.html)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>Wormhole used for maps rendering. |
| [PointAdapter](-point-adapter/index.html) | [jvm]<br>class [PointAdapter](-point-adapter/index.html)<[P](-point-adapter/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Adapts various representations of bidimensional positions. |
| [PointerSpeedImpl](-pointer-speed-impl/index.html) | [jvm]<br>class [PointerSpeedImpl](-pointer-speed-impl/index.html) : [PointerSpeed](../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.html)<br>Implementation for [PointerSpeed](../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.html) interface. |
| [WormholeSwing](-wormhole-swing/index.html) | [jvm]<br>open class [WormholeSwing](-wormhole-swing/index.html)<[P](-wormhole-swing/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](-wormhole-swing/index.html)>?> : [AbstractWormhole2D](-abstract-wormhole2-d/index.html)<[P](-wormhole-swing/index.html)> <br>An implementation of [AbstractWormhole2D] for Swing. |

