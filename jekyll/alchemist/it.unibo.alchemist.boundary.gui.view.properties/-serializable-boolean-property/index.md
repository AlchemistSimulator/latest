---
title: SerializableBooleanProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[SerializableBooleanProperty](index.html)



# SerializableBooleanProperty



[jvm]\
open class [SerializableBooleanProperty](index.html) : BooleanPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

javafx.beans.property.SimpleBooleanProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).



## Constructors


| | |
|---|---|
| [SerializableBooleanProperty](-serializable-boolean-property.html) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.html)()<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.html) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.html)(initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.html) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.html) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>The constructor of {@code SimpleBooleanProperty}. |


## Functions


| Name | Summary |
|---|---|
| [addListener](index.html#1504033421%2FFunctions%2F-134779887) | [jvm]<br>open fun [addListener](index.html#1504033421%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [and](index.html#1213835824%2FFunctions%2F-134779887) | [jvm]<br>open fun [and](index.html#1213835824%2FFunctions%2F-134779887)(p: ObservableBooleanValue): BooleanBinding |
| [asObject](index.html#1776861454%2FFunctions%2F-134779887) | [jvm]<br>open fun [asObject](index.html#1776861454%2FFunctions%2F-134779887)(): ObjectExpression<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>open fun [asObject](index.html#44561349%2FFunctions%2F-134779887)(): ObjectProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>open fun [asObject](index.html#-860701053%2FFunctions%2F-134779887)(): ReadOnlyObjectProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)> |
| [asString](index.html#904246396%2FFunctions%2F-134779887) | [jvm]<br>open fun [asString](index.html#904246396%2FFunctions%2F-134779887)(): StringBinding |
| [bind](index.html#-679939498%2FFunctions%2F-134779887) | [jvm]<br>open fun [bind](index.html#-679939498%2FFunctions%2F-134779887)(p: ObservableValue<out [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |
| [bindBidirectional](index.html#-778752377%2FFunctions%2F-134779887) | [jvm]<br>open fun [bindBidirectional](index.html#-778752377%2FFunctions%2F-134779887)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |
| [booleanExpression](index.html#-444975239%2FFunctions%2F-134779887) | [jvm]<br>open fun [booleanExpression](index.html#-444975239%2FFunctions%2F-134779887)(p: ObservableBooleanValue): BooleanExpression |
| [booleanProperty](index.html#1077087774%2FFunctions%2F-134779887) | [jvm]<br>open fun [booleanProperty](index.html#1077087774%2FFunctions%2F-134779887)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): BooleanProperty |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.html#-1086264515%2FFunctions%2F-134779887) | [jvm]<br>open fun [get](index.html#-1086264515%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBean](get-bean.html) | [jvm]<br>open fun [getBean](get-bean.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getTypeAdapter](get-type-adapter.html) | [jvm]<br>open fun [getTypeAdapter](get-type-adapter.html)(): [PropertyTypeAdapter](../-property-type-adapter/index.html)<[SerializableBooleanProperty](index.html)><br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code SerializableBooleanProperty}. |
| [getValue](index.html#-171963740%2FFunctions%2F-134779887) | [jvm]<br>open fun [getValue](index.html#-171963740%2FFunctions%2F-134779887)(): [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)<br>abstract fun [getValue](index.html#414617374%2FFunctions%2F-134779887)(): T |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.html#949565151%2FFunctions%2F-134779887) | [jvm]<br>open fun [isBound](index.html#949565151%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEqualTo](index.html#-145154146%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEqualTo](index.html#-145154146%2FFunctions%2F-134779887)(p: ObservableBooleanValue): BooleanBinding |
| [isNotEqualTo](index.html#-212114533%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEqualTo](index.html#-212114533%2FFunctions%2F-134779887)(p: ObservableBooleanValue): BooleanBinding |
| [not](index.html#-221031224%2FFunctions%2F-134779887) | [jvm]<br>open fun [not](index.html#-221031224%2FFunctions%2F-134779887)(): BooleanBinding |
| [or](index.html#-1504952200%2FFunctions%2F-134779887) | [jvm]<br>open fun [or](index.html#-1504952200%2FFunctions%2F-134779887)(p: ObservableBooleanValue): BooleanBinding |
| [readOnlyBooleanProperty](index.html#530614172%2FFunctions%2F-134779887) | [jvm]<br>open fun [readOnlyBooleanProperty](index.html#530614172%2FFunctions%2F-134779887)(p: ReadOnlyProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): ReadOnlyBooleanProperty |
| [removeListener](index.html#-1900269540%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeListener](index.html#-1900269540%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [set](index.html#73645897%2FFunctions%2F-134779887) | [jvm]<br>open fun [set](index.html#73645897%2FFunctions%2F-134779887)(p: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setValue](index.html#1300363943%2FFunctions%2F-134779887) | [jvm]<br>open fun [setValue](index.html#1300363943%2FFunctions%2F-134779887)(p: [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)) |
| [toString](index.html#-583567749%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#-583567749%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.html#586401873%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbind](index.html#586401873%2FFunctions%2F-134779887)() |
| [unbindBidirectional](index.html#-1344338418%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbindBidirectional](index.html#-1344338418%2FFunctions%2F-134779887)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |


## Properties


| Name | Summary |
|---|---|
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

