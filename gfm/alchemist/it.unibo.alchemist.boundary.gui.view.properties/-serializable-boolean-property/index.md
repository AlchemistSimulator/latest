//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[SerializableBooleanProperty](index.md)

# SerializableBooleanProperty

[jvm]\
open class [SerializableBooleanProperty](index.md) : BooleanPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

javafx.beans.property.SimpleBooleanProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).

## Constructors

| | |
|---|---|
| [SerializableBooleanProperty](-serializable-boolean-property.md) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.md)()<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.md) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.md)(initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.md) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleBooleanProperty}. |
| [SerializableBooleanProperty](-serializable-boolean-property.md) | [jvm]<br>open fun [SerializableBooleanProperty](-serializable-boolean-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>The constructor of {@code SimpleBooleanProperty}. |

## Functions

| Name | Summary |
|---|---|
| [addListener](index.md#1504033421%2FFunctions%2F-267951372) | [jvm]<br>open fun [addListener](index.md#1504033421%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [and](index.md#1213835824%2FFunctions%2F-267951372) | [jvm]<br>open fun [and](index.md#1213835824%2FFunctions%2F-267951372)(p: ObservableBooleanValue): BooleanBinding |
| [asObject](index.md#1776861454%2FFunctions%2F-267951372) | [jvm]<br>open fun [asObject](index.md#1776861454%2FFunctions%2F-267951372)(): ObjectExpression<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>open fun [asObject](index.md#44561349%2FFunctions%2F-267951372)(): ObjectProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)><br>open fun [asObject](index.md#-860701053%2FFunctions%2F-267951372)(): ReadOnlyObjectProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)> |
| [asString](index.md#904246396%2FFunctions%2F-267951372) | [jvm]<br>open fun [asString](index.md#904246396%2FFunctions%2F-267951372)(): StringBinding |
| [bind](index.md#-679939498%2FFunctions%2F-267951372) | [jvm]<br>open fun [bind](index.md#-679939498%2FFunctions%2F-267951372)(p: ObservableValue<out [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |
| [bindBidirectional](index.md#-778752377%2FFunctions%2F-267951372) | [jvm]<br>open fun [bindBidirectional](index.md#-778752377%2FFunctions%2F-267951372)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |
| [booleanExpression](index.md#-444975239%2FFunctions%2F-267951372) | [jvm]<br>open fun [booleanExpression](index.md#-444975239%2FFunctions%2F-267951372)(p: ObservableBooleanValue): BooleanExpression |
| [booleanProperty](index.md#1077087774%2FFunctions%2F-267951372) | [jvm]<br>open fun [booleanProperty](index.md#1077087774%2FFunctions%2F-267951372)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): BooleanProperty |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.md#-1086264515%2FFunctions%2F-267951372) | [jvm]<br>open fun [get](index.md#-1086264515%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getBean](get-bean.md) | [jvm]<br>open fun [getBean](get-bean.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](../-serializable-enum-property/index.md#-1148459777%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getName](../-serializable-enum-property/index.md#-1148459777%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getTypeAdapter](get-type-adapter.md) | [jvm]<br>open fun [getTypeAdapter](get-type-adapter.md)(): [PropertyTypeAdapter](../-property-type-adapter/index.md)<[SerializableBooleanProperty](index.md)><br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code SerializableBooleanProperty}. |
| [getValue](index.md#-171963740%2FFunctions%2F-267951372) | [jvm]<br>open fun [getValue](index.md#-171963740%2FFunctions%2F-267951372)(): [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)<br>abstract fun [getValue](index.md#414617374%2FFunctions%2F-267951372)(): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.md#949565151%2FFunctions%2F-267951372) | [jvm]<br>open fun [isBound](index.md#949565151%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEqualTo](index.md#-145154146%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEqualTo](index.md#-145154146%2FFunctions%2F-267951372)(p: ObservableBooleanValue): BooleanBinding |
| [isNotEqualTo](index.md#-212114533%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotEqualTo](index.md#-212114533%2FFunctions%2F-267951372)(p: ObservableBooleanValue): BooleanBinding |
| [not](index.md#-221031224%2FFunctions%2F-267951372) | [jvm]<br>open fun [not](index.md#-221031224%2FFunctions%2F-267951372)(): BooleanBinding |
| [or](index.md#-1504952200%2FFunctions%2F-267951372) | [jvm]<br>open fun [or](index.md#-1504952200%2FFunctions%2F-267951372)(p: ObservableBooleanValue): BooleanBinding |
| [readOnlyBooleanProperty](index.md#530614172%2FFunctions%2F-267951372) | [jvm]<br>open fun [readOnlyBooleanProperty](index.md#530614172%2FFunctions%2F-267951372)(p: ReadOnlyProperty<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): ReadOnlyBooleanProperty |
| [removeListener](index.md#-1900269540%2FFunctions%2F-267951372) | [jvm]<br>open fun [removeListener](index.md#-1900269540%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [set](index.md#73645897%2FFunctions%2F-267951372) | [jvm]<br>open fun [set](index.md#73645897%2FFunctions%2F-267951372)(p: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setValue](index.md#1300363943%2FFunctions%2F-267951372) | [jvm]<br>open fun [setValue](index.md#1300363943%2FFunctions%2F-267951372)(p: [Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)) |
| [toString](index.md#-583567749%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](index.md#-583567749%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.md#586401873%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbind](index.md#586401873%2FFunctions%2F-267951372)() |
| [unbindBidirectional](index.md#-1344338418%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbindBidirectional](index.md#-1344338418%2FFunctions%2F-267951372)(p: Property<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>) |

## Properties

| Name | Summary |
|---|---|
| [name](name.md) | [jvm]<br>private open var [name](name.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
