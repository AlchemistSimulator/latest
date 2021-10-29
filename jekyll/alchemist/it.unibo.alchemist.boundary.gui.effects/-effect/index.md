---
title: Effect
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[Effect](index.html)



# Effect



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~interface~~ [~~Effect~~](index.html) ~~:~~ [~~Serializable~~](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Functions


| Name | Summary |
|---|---|
| [apply](apply.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](apply.html), [P](apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>?> [apply](apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>)<br>Applies the effect. |
| [equals](equals.html) | [jvm]<br>abstract fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](get-color-summary.html) | [jvm]<br>abstract fun [getColorSummary](get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](hash-code.html) | [jvm]<br>abstract fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [DrawSmartcam](../-draw-smartcam/index.html) |
| [DrawLayers](../-draw-layers/index.html) |
| [DrawShape](../-draw-shape/index.html) |
| [DrawOnce](../-draw-once/index.html) |

