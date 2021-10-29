//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawPedestrianPath](index.md)

# DrawPedestrianPath

[jvm]\
open class [DrawPedestrianPath](index.md) : [DrawOnce](../-draw-once/index.md)

Draws the paths took by pedestrians.

## Functions

| Name | Summary |
|---|---|
| [apply](../-draw-once/apply.md) | [jvm]<br>open fun <[T](../-draw-once/apply.md), [P](../-draw-once/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](../-draw-once/apply.md)(graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~open~~ ~~fun~~ [~~apply~~](../-effect/apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~<br>open fun <[T](../-effect/apply.md), [P](../-effect/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](../-effect/apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)<br>Applies the effect. |
| [equals](../-effect/equals.md) | [jvm]<br>abstract fun [equals](../-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorSummary](get-color-summary.md) | [jvm]<br>open fun [getColorSummary](get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html) |
| [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.md#470324422%2FFunctions%2F-267951372) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>open fun [getMarkerNodeID](../-draw-bidimensional-gaussian-layers-gradient/index.md#470324422%2FFunctions%2F-267951372)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>the marker node id |
| [hashCode](../-effect/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isToBeDrawn](is-to-be-drawn.md) | [jvm]<br>open fun [isToBeDrawn](is-to-be-drawn.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>if it is to be drawn |

## Properties

| Name | Summary |
|---|---|
| [alpha](alpha.md) | [jvm]<br>private open var [alpha](alpha.md): RangedInteger |
| [blue](blue.md) | [jvm]<br>private open var [blue](blue.md): RangedInteger |
| [green](green.md) | [jvm]<br>private open var [green](green.md): RangedInteger |
| [red](red.md) | [jvm]<br>private open var [red](red.md): RangedInteger |
| [toBeDrawn](to-be-drawn.md) | [jvm]<br>private open var [toBeDrawn](to-be-drawn.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
