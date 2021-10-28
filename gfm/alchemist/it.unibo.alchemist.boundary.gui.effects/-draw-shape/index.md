//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawShape](index.md)

# DrawShape

[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()

~~class~~ [~~DrawShape~~](index.md) ~~:~~ [~~Effect~~](../-effect/index.md)

## Constructors

| | |
|---|---|
| [DrawShape](-draw-shape.md) | [jvm]<br>open fun [DrawShape](-draw-shape.md)()<br>Builds a new [DrawShape](index.md) effect. |

## Types

| Name | Summary |
|---|---|
| [Mode](-mode/index.md) | [jvm]<br>enum [Mode](-mode/index.md) |

## Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | [jvm]<br>open fun [apply](apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun <[T](../-effect/apply.md), [P](../-effect/apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> [apply](../-effect/apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>)<br>Applies the effect. |
| [equals](../-effect/equals.md) | [jvm]<br>abstract fun [equals](../-effect/equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorChannel](get-color-channel.md) | [jvm]<br>open fun [getColorChannel](get-color-channel.md)(): [ColorChannel](../../it.unibo.alchemist.boundary.gui/-color-channel/index.md)<br>Color Channel |
| [getColorSummary](get-color-summary.md) | [jvm]<br>open fun [getColorSummary](get-color-summary.md)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.md) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isMolFilter](is-mol-filter.md) | [jvm]<br>open fun [isMolFilter](is-mol-filter.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>molFilter |
| [isMolPropertyFilter](is-mol-property-filter.md) | [jvm]<br>open fun [isMolPropertyFilter](is-mol-property-filter.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>molPropertyFilter |
| [isReverse](is-reverse.md) | [jvm]<br>open fun [isReverse](is-reverse.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>reverse |
| [isWritingPropertyValue](is-writing-property-value.md) | [jvm]<br>open fun [isWritingPropertyValue](is-writing-property-value.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if it is writing the property value |

## Properties

| Name | Summary |
|---|---|
| [alpha](alpha.md) | [jvm]<br>private open var [alpha](alpha.md): RangedInteger |
| [blue](blue.md) | [jvm]<br>private open var [blue](blue.md): RangedInteger |
| [c](c.md) | [jvm]<br>private open var [c](c.md): [ColorChannel](../../it.unibo.alchemist.boundary.gui/-color-channel/index.md) |
| [green](green.md) | [jvm]<br>private open var [green](green.md): RangedInteger |
| [incarnation](incarnation.md) | [jvm]<br>private open var [incarnation](incarnation.md): [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [maxprop](maxprop.md) | [jvm]<br>private open var [maxprop](maxprop.md): RangedInteger |
| [minprop](minprop.md) | [jvm]<br>private open var [minprop](minprop.md): RangedInteger |
| [mode](mode.md) | [jvm]<br>private open var [mode](mode.md): [DrawShape.Mode](-mode/index.md) |
| [molecule](molecule.md) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>private open val [molecule](molecule.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) |
| [molFilter](mol-filter.md) | [jvm]<br>private open var [molFilter](mol-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molPropertyFilter](mol-property-filter.md) | [jvm]<br>private open var [molPropertyFilter](mol-property-filter.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molString](mol-string.md) | [jvm]<br>private open var [molString](mol-string.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [property](property.md) | [jvm]<br>private open var [property](property.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [propoom](propoom.md) | [jvm]<br>private open var [propoom](propoom.md): RangedInteger |
| [red](red.md) | [jvm]<br>private open var [red](red.md): RangedInteger |
| [reverse](reverse.md) | [jvm]<br>private open var [reverse](reverse.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [scaleFactor](scale-factor.md) | [jvm]<br>private open var [scaleFactor](scale-factor.md): RangedInteger |
| [size](size.md) | [jvm]<br>private open var [size](size.md): RangedInteger |
| [writingPropertyValue](writing-property-value.md) | [jvm]<br>private open var [writingPropertyValue](writing-property-value.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
