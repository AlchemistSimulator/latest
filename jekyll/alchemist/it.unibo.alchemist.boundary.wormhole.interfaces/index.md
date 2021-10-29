---
title: it.unibo.alchemist.boundary.wormhole.interfaces
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.wormhole.interfaces](index.html)



# Package it.unibo.alchemist.boundary.wormhole.interfaces



## Types


| Name | Summary |
|---|---|
| [AngleManager](-angle-manager/index.html) | [jvm]<br>interface [AngleManager](-angle-manager/index.html) : [SlideInputManager](-slide-input-manager/index.html)<br>A class that implements the IAngleManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents an angle. |
| [PointerSpeed](-pointer-speed/index.html) | [jvm]<br>interface [PointerSpeed](-pointer-speed/index.html)<br>Base type for any pointing device: it provides services to analyze the pointer's movement. |
| [SlideInputManager](-slide-input-manager/index.html) | [jvm]<br>interface [SlideInputManager](-slide-input-manager/index.html)<br>ISlideInputManager is the base type for any class whose aim is to handle the the sliding of any physical/virtual device/control. |
| [ViewPort](-view-port/index.html) | [jvm]<br>interface [ViewPort](-view-port/index.html)<br>This interface implements an Adapter pattern between a generic view element and the needs of a [Wormhole2D](-wormhole2-d/index.html). |
| [Wormhole2D](-wormhole2-d/index.html) | [jvm]<br>interface [Wormhole2D](-wormhole2-d/index.html)<[P](-wormhole2-d/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](-wormhole2-d/index.html)>?><br>A Wormhole (in this context) is an entity that "connects" two worlds: the "environment" and the "view". |
| [ZoomManager](-zoom-manager/index.html) | [jvm]<br>interface [ZoomManager](-zoom-manager/index.html) : [SlideInputManager](-slide-input-manager/index.html)<br>A class that implements the IZoomManager interface is able to convert the sliding of any physical/virtual device/control into a positive double value that represents a zoom rate. |

