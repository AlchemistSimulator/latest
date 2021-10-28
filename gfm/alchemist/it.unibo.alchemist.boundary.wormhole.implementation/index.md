//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](index.md)

# Package it.unibo.alchemist.boundary.wormhole.implementation

## Types

| Name | Summary |
|---|---|
| [AbstractSlideInputManager](-abstract-slide-input-manager/index.md) | [jvm]<br>open class [AbstractSlideInputManager](-abstract-slide-input-manager/index.md) : [SlideInputManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-slide-input-manager/index.md)<br>ASlideInputManager is the base class for any class whose aim is to handle the the sliding of any physical/virtual device/control. |
| [AbstractWormhole2D](-abstract-wormhole2-d/index.md) | [jvm]<br>abstract class [AbstractWormhole2D](-abstract-wormhole2-d/index.md)<[P](-abstract-wormhole2-d/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](-point-adapter/index.md)>?> : [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](-point-adapter/index.md)> <br>Partial, abstract, implementation for the interface [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md). |
| [AngleManagerImpl](-angle-manager-impl/index.md) | [jvm]<br>class [AngleManagerImpl](-angle-manager-impl/index.md) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.md), [AngleManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-angle-manager/index.md)<br>An AngleManager converts the sliding of any physical/virtual device/control into an angle expressed with radians. |
| [DoubleDimension](-double-dimension/index.md) | [jvm]<br>class [DoubleDimension](-double-dimension/index.md) : [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html)<br>Implementation of the [Dimension2D](https://docs.oracle.com/javase/8/docs/api/java/awt/geom/Dimension2D.html) abstract class with double precision. |
| [ExponentialZoomManager](-exponential-zoom-manager/index.md) | [jvm]<br>class [ExponentialZoomManager](-exponential-zoom-manager/index.md) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.md), [ZoomManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md)<br>An ExpZoomManager converts the sliding of any physical/virtual device/control into a zoom rate through an exponential function (in this way I am sure to not see negative values ;-). |
| [LinearZoomManager](-linear-zoom-manager/index.md) | [jvm]<br>class [LinearZoomManager](-linear-zoom-manager/index.md) : [AbstractSlideInputManager](-abstract-slide-input-manager/index.md), [ZoomManager](../it.unibo.alchemist.boundary.wormhole.interfaces/-zoom-manager/index.md)<br>A [LinearZoomManager](-linear-zoom-manager/index.md) converts the sliding of any physical/virtual device/control into a zoom rate through a linear function. |
| [MapWormhole](-map-wormhole/index.md) | [jvm]<br>class [MapWormhole](-map-wormhole/index.md) : [WormholeSwing](-wormhole-swing/index.md)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> <br>Wormhole used for maps rendering. |
| [PointAdapter](-point-adapter/index.md) | [jvm]<br>class [PointAdapter](-point-adapter/index.md)<[P](-point-adapter/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](-point-adapter/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Adapts various representations of bidimensional positions. |
| [PointerSpeedImpl](-pointer-speed-impl/index.md) | [jvm]<br>class [PointerSpeedImpl](-pointer-speed-impl/index.md) : [PointerSpeed](../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.md)<br>Implementation for [PointerSpeed](../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.md) interface. |
| [WormholeSwing](-wormhole-swing/index.md) | [jvm]<br>open class [WormholeSwing](-wormhole-swing/index.md)<[P](-wormhole-swing/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> : [AbstractWormhole2D](-abstract-wormhole2-d/index.md)<[P](../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)> <br>An implementation of [AbstractWormhole2D] for Swing. |