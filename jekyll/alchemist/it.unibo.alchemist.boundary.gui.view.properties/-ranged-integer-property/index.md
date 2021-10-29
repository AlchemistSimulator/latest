---
title: RangedIntegerProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[RangedIntegerProperty](index.html)



# RangedIntegerProperty



[jvm]\
open class [RangedIntegerProperty](index.html) : IntegerPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

This javafx.beans.property.IntegerProperty is designed to have a range for the wrapped value and to be serializable.



## Constructors


| | |
|---|---|
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Based on constructor of IntegerPropertyBase, adds the specified bounds. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Based on constructor of IntegerPropertyBase, adds the specified bounds. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Based on constructor of IntegerPropertyBase, adds the specified bounds. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(lowerBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), upperBound: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Based on constructor of IntegerPropertyBase, adds the specified bounds. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>The constructor of IntegerPropertyBase. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of IntegerPropertyBase. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)(initialValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>The constructor of IntegerPropertyBase. |
| [RangedIntegerProperty](-ranged-integer-property.html) | [jvm]<br>open fun [RangedIntegerProperty](-ranged-integer-property.html)()<br>The constructor of IntegerPropertyBase. |


## Functions


| Name | Summary |
|---|---|
| [add](index.html#1026205619%2FFunctions%2F-134779887) | [jvm]<br>open fun [add](index.html#1026205619%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): DoubleBinding<br>open fun [add](index.html#-1818793662%2FFunctions%2F-134779887)(p: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): FloatBinding<br>open fun [add](index.html#1950662031%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): IntegerBinding<br>open fun [add](index.html#1187321192%2FFunctions%2F-134779887)(p: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): LongBinding<br>open fun [add](index.html#838702503%2FFunctions%2F-134779887)(p: ObservableNumberValue): NumberBinding |
| [addListener](index.html#-981383645%2FFunctions%2F-134779887) | [jvm]<br>open fun [addListener](index.html#-981383645%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [asObject](index.html#-175633116%2FFunctions%2F-134779887) | [jvm]<br>open fun [asObject](index.html#-175633116%2FFunctions%2F-134779887)(): ObjectExpression<[Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)><br>open fun [asObject](index.html#-726184613%2FFunctions%2F-134779887)(): ObjectProperty<[Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)><br>open fun [asObject](index.html#-1631447015%2FFunctions%2F-134779887)(): ReadOnlyObjectProperty<[Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)> |
| [asString](../-ranged-double-property/index.html#1343929164%2FFunctions%2F-134779887) | [jvm]<br>open fun [asString](../-ranged-double-property/index.html#1343929164%2FFunctions%2F-134779887)(): StringBinding |
| [bind](index.html#2095390199%2FFunctions%2F-134779887) | [jvm]<br>open fun [bind](index.html#2095390199%2FFunctions%2F-134779887)(p: ObservableValue<out [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>) |
| [bindBidirectional](index.html#1728926650%2FFunctions%2F-134779887) | [jvm]<br>open fun [bindBidirectional](index.html#1728926650%2FFunctions%2F-134779887)(p: Property<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>) |
| [divide](index.html#-163604853%2FFunctions%2F-134779887) | [jvm]<br>open fun [divide](index.html#-163604853%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): DoubleBinding<br>open fun [divide](index.html#1329413994%2FFunctions%2F-134779887)(p: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): FloatBinding<br>open fun [divide](index.html#1480195511%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): IntegerBinding<br>open fun [divide](index.html#-512239040%2FFunctions%2F-134779887)(p: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): LongBinding<br>open fun [divide](index.html#-1103646029%2FFunctions%2F-134779887)(p: ObservableNumberValue): NumberBinding |
| [doubleValue](index.html#1875547717%2FFunctions%2F-134779887) | [jvm]<br>open fun [doubleValue](index.html#1875547717%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [floatValue](index.html#785655104%2FFunctions%2F-134779887) | [jvm]<br>open fun [floatValue](index.html#785655104%2FFunctions%2F-134779887)(): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [get](index.html#2075461351%2FFunctions%2F-134779887) | [jvm]<br>open fun [get](index.html#2075461351%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getBean](get-bean.html) | [jvm]<br>open fun [getBean](get-bean.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getTypeAdapter](get-type-adapter.html) | [jvm]<br>open fun [getTypeAdapter](get-type-adapter.html)(): [PropertyTypeAdapter](../-property-type-adapter/index.html)<[RangedIntegerProperty](index.html)><br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code RangedIntegerProperty}. |
| [getValue](index.html#-2124458310%2FFunctions%2F-134779887) | [jvm]<br>open fun [getValue](index.html#-2124458310%2FFunctions%2F-134779887)(): [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)<br>abstract fun [getValue](../-serializable-boolean-property/index.html#414617374%2FFunctions%2F-134779887)(): T |
| [greaterThan](index.html#-855788851%2FFunctions%2F-134779887) | [jvm]<br>open fun [greaterThan](index.html#-855788851%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [greaterThanOrEqualTo](index.html#976735163%2FFunctions%2F-134779887) | [jvm]<br>open fun [greaterThanOrEqualTo](index.html#976735163%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [integerExpression](index.html#-1835876805%2FFunctions%2F-134779887) | [jvm]<br>open fun [integerExpression](index.html#-1835876805%2FFunctions%2F-134779887)(p: ObservableIntegerValue): IntegerExpression |
| [integerProperty](index.html#-699536288%2FFunctions%2F-134779887) | [jvm]<br>open fun [integerProperty](index.html#-699536288%2FFunctions%2F-134779887)(p: Property<[Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>): IntegerProperty |
| [intValue](index.html#1187057043%2FFunctions%2F-134779887) | [jvm]<br>open fun [intValue](index.html#1187057043%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.html#551775625%2FFunctions%2F-134779887) | [jvm]<br>open fun [isBound](index.html#551775625%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEqualTo](index.html#331049987%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEqualTo](index.html#331049987%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [isNotEqualTo](index.html#831479814%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEqualTo](index.html#831479814%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [lessThan](index.html#167802866%2FFunctions%2F-134779887) | [jvm]<br>open fun [lessThan](index.html#167802866%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [lessThanOrEqualTo](index.html#1377828918%2FFunctions%2F-134779887) | [jvm]<br>open fun [lessThanOrEqualTo](index.html#1377828918%2FFunctions%2F-134779887)(p: ObservableNumberValue): BooleanBinding |
| [longValue](index.html#-1941852752%2FFunctions%2F-134779887) | [jvm]<br>open fun [longValue](index.html#-1941852752%2FFunctions%2F-134779887)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [multiply](index.html#-402669184%2FFunctions%2F-134779887) | [jvm]<br>open fun [multiply](index.html#-402669184%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): DoubleBinding<br>open fun [multiply](index.html#906060245%2FFunctions%2F-134779887)(p: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): FloatBinding<br>open fun [multiply](index.html#1810480866%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): IntegerBinding<br>open fun [multiply](index.html#1136672373%2FFunctions%2F-134779887)(p: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): LongBinding<br>open fun [multiply](index.html#-1461585432%2FFunctions%2F-134779887)(p: ObservableNumberValue): NumberBinding |
| [negate](index.html#-530150573%2FFunctions%2F-134779887) | [jvm]<br>open fun [negate](index.html#-530150573%2FFunctions%2F-134779887)(): IntegerBinding<br>abstract fun [negate](index.html#-1238889060%2FFunctions%2F-134779887)(): NumberBinding |
| [numberExpression](index.html#1786898155%2FFunctions%2F-134779887) | [jvm]<br>open fun <[S](index.html#1786898155%2FFunctions%2F-134779887) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> [numberExpression](index.html#1786898155%2FFunctions%2F-134779887)(p: ObservableNumberValue): NumberExpressionBase |
| [readOnlyIntegerProperty](index.html#970937032%2FFunctions%2F-134779887) | [jvm]<br>open fun <[T](index.html#970937032%2FFunctions%2F-134779887) : [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)?> [readOnlyIntegerProperty](index.html#970937032%2FFunctions%2F-134779887)(p: ReadOnlyProperty<T>): ReadOnlyIntegerProperty |
| [removeListener](index.html#276100294%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeListener](index.html#276100294%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [set](set.html) | [jvm]<br>open fun [set](set.html)(value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>if the provided value is out of the specified range |
| [setValue](set-value.html) | [jvm]<br>open fun [setValue](set-value.html)(value: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html))<br>if the provided value is out of the specified range |
| [subtract](index.html#-860705136%2FFunctions%2F-134779887) | [jvm]<br>open fun [subtract](index.html#-860705136%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): DoubleBinding<br>open fun [subtract](index.html#-2018209083%2FFunctions%2F-134779887)(p: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)): FloatBinding<br>open fun [subtract](index.html#2106878930%2FFunctions%2F-134779887)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): IntegerBinding<br>open fun [subtract](index.html#1735077765%2FFunctions%2F-134779887)(p: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): LongBinding<br>open fun [subtract](index.html#-131751176%2FFunctions%2F-134779887)(p: ObservableNumberValue): NumberBinding |
| [toString](index.html#-30141167%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#-30141167%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.html#-1366092697%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbind](index.html#-1366092697%2FFunctions%2F-134779887)() |
| [unbindBidirectional](index.html#1303301331%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbindBidirectional](index.html#1303301331%2FFunctions%2F-134779887)(p: Property<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>) |


## Properties


| Name | Summary |
|---|---|
| [lowerBound](lower-bound.html) | [jvm]<br>private open var [lowerBound](lower-bound.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [upperBound](upper-bound.html) | [jvm]<br>private open var [upperBound](upper-bound.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

