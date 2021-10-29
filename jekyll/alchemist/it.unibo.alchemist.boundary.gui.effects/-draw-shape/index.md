---
title: DrawShape
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[DrawShape](index.html)



# DrawShape



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~class~~ [~~DrawShape~~](index.html) ~~:~~ [~~Effect~~](../-effect/index.html)



## Constructors


| | |
|---|---|
| [DrawShape](-draw-shape.html) | [jvm]<br>open fun [DrawShape](-draw-shape.html)()<br>Builds a new [DrawShape](index.html) effect. |


## Types


| Name | Summary |
|---|---|
| [Mode](-mode/index.html) | [jvm]<br>enum [Mode](-mode/index.html) |


## Functions


| Name | Summary |
|---|---|
| [apply](apply.html) | [jvm]<br>open fun [apply](apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun <[T](../-effect/apply.html), [P](../-effect/apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>?> [apply](../-effect/apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>)<br>Applies the effect. |
| [equals](../-effect/equals.html) | [jvm]<br>abstract fun [equals](../-effect/equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getColorChannel](get-color-channel.html) | [jvm]<br>open fun [getColorChannel](get-color-channel.html)(): [ColorChannel](../../it.unibo.alchemist.boundary.gui/-color-channel/index.html)<br>Color Channel |
| [getColorSummary](get-color-summary.html) | [jvm]<br>open fun [getColorSummary](get-color-summary.html)(): [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)<br>a color which resembles the color of this effect |
| [hashCode](../-effect/hash-code.html) | [jvm]<br>abstract fun [hashCode](../-effect/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isMolFilter](is-mol-filter.html) | [jvm]<br>open fun [isMolFilter](is-mol-filter.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>molFilter |
| [isMolPropertyFilter](is-mol-property-filter.html) | [jvm]<br>open fun [isMolPropertyFilter](is-mol-property-filter.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>molPropertyFilter |
| [isReverse](is-reverse.html) | [jvm]<br>open fun [isReverse](is-reverse.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>reverse |
| [isWritingPropertyValue](is-writing-property-value.html) | [jvm]<br>open fun [isWritingPropertyValue](is-writing-property-value.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if it is writing the property value |


## Properties


| Name | Summary |
|---|---|
| [alpha](alpha.html) | [jvm]<br>private open var [alpha](alpha.html): RangedInteger |
| [blue](blue.html) | [jvm]<br>private open var [blue](blue.html): RangedInteger |
| [c](c.html) | [jvm]<br>private open var [c](c.html): [ColorChannel](../../it.unibo.alchemist.boundary.gui/-color-channel/index.html) |
| [green](green.html) | [jvm]<br>private open var [green](green.html): RangedInteger |
| [incarnation](incarnation.html) | [jvm]<br>private open var [incarnation](incarnation.html): [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [maxprop](maxprop.html) | [jvm]<br>private open var [maxprop](maxprop.html): RangedInteger |
| [minprop](minprop.html) | [jvm]<br>private open var [minprop](minprop.html): RangedInteger |
| [mode](mode.html) | [jvm]<br>private open var [mode](mode.html): [DrawShape.Mode](-mode/index.html) |
| [molecule](molecule.html) | [jvm]<br>@[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()<br>private open val [molecule](molecule.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) |
| [molFilter](mol-filter.html) | [jvm]<br>private open var [molFilter](mol-filter.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molPropertyFilter](mol-property-filter.html) | [jvm]<br>private open var [molPropertyFilter](mol-property-filter.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [molString](mol-string.html) | [jvm]<br>private open var [molString](mol-string.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [property](property.html) | [jvm]<br>private open var [property](property.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [propoom](propoom.html) | [jvm]<br>private open var [propoom](propoom.html): RangedInteger |
| [red](red.html) | [jvm]<br>private open var [red](red.html): RangedInteger |
| [reverse](reverse.html) | [jvm]<br>private open var [reverse](reverse.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [scaleFactor](scale-factor.html) | [jvm]<br>private open var [scaleFactor](scale-factor.html): RangedInteger |
| [size](size.html) | [jvm]<br>private open var [size](size.html): RangedInteger |
| [writingPropertyValue](writing-property-value.html) | [jvm]<br>private open var [writingPropertyValue](writing-property-value.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

