//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[Effect](index.md)

# Effect

[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()

~~interface~~ [~~Effect~~](index.md) ~~:~~ [~~Serializable~~](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](apply.md), [P](apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-map-display/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-map-display/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>Applies the effect. |
| [equals](equals.md) | [jvm]<br>abstract fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](get-color-summary.md) | [jvm]<br>abstract fun [getColorSummary](get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](hash-code.md) | [jvm]<br>abstract fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [DrawSmartcam](../-draw-smartcam/index.md) |
| [DrawLayers](../-draw-layers/index.md) |
| [DrawShape](../-draw-shape/index.md) |
| [DrawOnce](../-draw-once/index.md) |
