---
title: it.unibo.alchemist.boundary.interactions
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.interactions](index.html)



# Package it.unibo.alchemist.boundary.interactions



## Types


| Name | Summary |
|---|---|
| [AnalogPanHelper](-analog-pan-helper/index.html) | [jvm]<br>class [AnalogPanHelper](-analog-pan-helper/index.html)(**current**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Helps manage panning done through the mouse, therefore analog in the sense that the panning can go towards any direction. |
| [BaseInteractionManager](-base-interaction-manager/index.html) | [jvm]<br>class [BaseInteractionManager](-base-interaction-manager/index.html)<[T](-base-interaction-manager/index.html), [P](-base-interaction-manager/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-base-interaction-manager/index.html)>>(**monitor**: [AbstractFXDisplay](../it.unibo.alchemist.boundary.monitors/-abstract-f-x-display/index.html)<[T](-base-interaction-manager/index.html), [P](-base-interaction-manager/index.html)>) : [InteractionManager](-interaction-manager/index.html)<[T](-base-interaction-manager/index.html), [P](-base-interaction-manager/index.html)> <br>An interaction manager that implements pan, select, move, delete and zoom. |
| [DigitalPanManager](-digital-pan-manager/index.html) | [jvm]<br>class [DigitalPanManager](-digital-pan-manager/index.html)<[P](-digital-pan-manager/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-digital-pan-manager/index.html)>>(**speed**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **period**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **wormhole**: [Wormhole2D](../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](-digital-pan-manager/index.html)>, **updates**: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>Manages panning towards a cardinal (N, S, E, W) or intercardinal (NE, NW, SE, SW) direction. |
| [Direction2D](-direction2-d/index.html) | [jvm]<br>enum [Direction2D](-direction2-d/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Direction2D](-direction2-d/index.html)> <br>Cardinal and intercardinal directions indicating a movement. |
| [InteractionManager](-interaction-manager/index.html) | [jvm]<br>interface [InteractionManager](-interaction-manager/index.html)<[T](-interaction-manager/index.html), [P](-interaction-manager/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-interaction-manager/index.html)>><br>An interaction manager that controls the input/output on the environment done through the GUI. |
| [SelectionHelper](-selection-helper/index.html) | [jvm]<br>class [SelectionHelper](-selection-helper/index.html)<[T](-selection-helper/index.html), [P](-selection-helper/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](-selection-helper/index.html)>><br>Manages multi-element selection and click-selection. |

