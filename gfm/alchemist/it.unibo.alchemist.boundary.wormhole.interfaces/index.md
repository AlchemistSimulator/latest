//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](index.md)

# Package it.unibo.alchemist.boundary.wormhole.interfaces

## Types

| Name | Summary |
|---|---|
| [AngleManager](-angle-manager/index.md) | [jvm]<br>interface [AngleManager](-angle-manager/index.md) : [SlideInputManager](-slide-input-manager/index.md)<br>A class that implements the IAngleManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents an angle. |
| [PointerSpeed](-pointer-speed/index.md) | [jvm]<br>interface [PointerSpeed](-pointer-speed/index.md)<br>Base type for any pointing device: it provides services to analyze the pointer's movement. |
| [SlideInputManager](-slide-input-manager/index.md) | [jvm]<br>interface [SlideInputManager](-slide-input-manager/index.md)<br>ISlideInputManager is the base type for any class whose aim is to handle the the sliding of any physical/virtual device/control. |
| [ViewPort](-view-port/index.md) | [jvm]<br>interface [ViewPort](-view-port/index.md)<br>This interface implements an Adapter pattern between a generic view element and the needs of a [Wormhole2D](-wormhole2-d/index.md). |
| [Wormhole2D](-wormhole2-d/index.md) | [jvm]<br>interface [Wormhole2D](-wormhole2-d/index.md)<[P](-wormhole2-d/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md)>?><br>A Wormhole (in this context) is an entity that "connects" two worlds: the "environment" and the "view". |
| [ZoomManager](-zoom-manager/index.md) | [jvm]<br>interface [ZoomManager](-zoom-manager/index.md) : [SlideInputManager](-slide-input-manager/index.md)<br>A class that implements the IZoomManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents a zoom rate. |
