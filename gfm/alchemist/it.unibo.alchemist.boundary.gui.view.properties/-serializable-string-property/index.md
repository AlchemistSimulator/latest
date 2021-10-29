//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[SerializableStringProperty](index.md)

# SerializableStringProperty

[jvm]\
open class [SerializableStringProperty](index.md) : StringPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

javafx.beans.property.SimpleStringProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).

## Constructors

| | |
|---|---|
| [SerializableStringProperty](-serializable-string-property.md) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.md)()<br>The constructor of {@code SimpleStringProperty}. |
| [SerializableStringProperty](-serializable-string-property.md) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.md)(initialValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleStringProperty}. |
| [SerializableStringProperty](-serializable-string-property.md) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleStringProperty}. |

## Functions

| Name | Summary |
|---|---|
| [addListener](index.md#-741023232%2FFunctions%2F-267951372) | [jvm]<br>open fun [addListener](index.md#-741023232%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [bind](index.md#1367372508%2FFunctions%2F-267951372) | [jvm]<br>open fun [bind](index.md#1367372508%2FFunctions%2F-267951372)(p: ObservableValue<out [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [bindBidirectional](index.md#-253756859%2FFunctions%2F-267951372) | [jvm]<br>open fun [bindBidirectional](index.md#-253756859%2FFunctions%2F-267951372)(p: Property<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [concat](index.md#1381068703%2FFunctions%2F-267951372) | [jvm]<br>open fun [concat](index.md#1381068703%2FFunctions%2F-267951372)(p: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): StringExpression |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.md#-1896285590%2FFunctions%2F-267951372) | [jvm]<br>open fun [get](index.md#-1896285590%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>abstract fun [get](index.md#-692577270%2FFunctions%2F-267951372)(): T |
| [getBean](get-bean.md) | [jvm]<br>open fun [getBean](get-bean.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](../-serializable-enum-property/index.md#-1148459777%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getName](../-serializable-enum-property/index.md#-1148459777%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getTypeAdapter](get-type-adapter.md) | [jvm]<br>open fun [getTypeAdapter](get-type-adapter.md)(): [PropertyTypeAdapter](../-property-type-adapter/index.md)<[SerializableStringProperty](index.md)><br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code SerializableStringProperty}. |
| [getValue](index.md#-584588405%2FFunctions%2F-267951372) | [jvm]<br>open fun [getValue](index.md#-584588405%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>abstract fun [getValue](../-serializable-boolean-property/index.md#414617374%2FFunctions%2F-267951372)(): T |
| [getValueSafe](index.md#1835836798%2FFunctions%2F-267951372) | [jvm]<br>fun [getValueSafe](index.md#1835836798%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [greaterThan](index.md#351412510%2FFunctions%2F-267951372) | [jvm]<br>open fun [greaterThan](index.md#351412510%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [greaterThanOrEqualTo](index.md#923048218%2FFunctions%2F-267951372) | [jvm]<br>open fun [greaterThanOrEqualTo](index.md#923048218%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.md#1110173580%2FFunctions%2F-267951372) | [jvm]<br>open fun [isBound](index.md#1110173580%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEmpty](index.md#-1787983215%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEmpty](index.md#-1787983215%2FFunctions%2F-267951372)(): BooleanBinding |
| [isEqualTo](index.md#623749268%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEqualTo](index.md#623749268%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [isEqualToIgnoreCase](index.md#1467134482%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEqualToIgnoreCase](index.md#1467134482%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [isNotEmpty](index.md#1746828194%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotEmpty](index.md#1746828194%2FFunctions%2F-267951372)(): BooleanBinding |
| [isNotEqualTo](index.md#1853469797%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotEqualTo](index.md#1853469797%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [isNotEqualToIgnoreCase](index.md#-735908701%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotEqualToIgnoreCase](index.md#-735908701%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [isNotNull](index.md#243776836%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotNull](index.md#243776836%2FFunctions%2F-267951372)(): BooleanBinding |
| [isNull](index.md#-424438667%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNull](index.md#-424438667%2FFunctions%2F-267951372)(): BooleanBinding |
| [length](index.md#-575804160%2FFunctions%2F-267951372) | [jvm]<br>open fun [length](index.md#-575804160%2FFunctions%2F-267951372)(): IntegerBinding |
| [lessThan](index.md#1905668049%2FFunctions%2F-267951372) | [jvm]<br>open fun [lessThan](index.md#1905668049%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [lessThanOrEqualTo](index.md#-1502977081%2FFunctions%2F-267951372) | [jvm]<br>open fun [lessThanOrEqualTo](index.md#-1502977081%2FFunctions%2F-267951372)(p: ObservableStringValue): BooleanBinding |
| [removeListener](index.md#1142681545%2FFunctions%2F-267951372) | [jvm]<br>open fun [removeListener](index.md#1142681545%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [set](index.md#412778713%2FFunctions%2F-267951372) | [jvm]<br>open fun [set](index.md#412778713%2FFunctions%2F-267951372)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [setValue](index.md#-1882089003%2FFunctions%2F-267951372) | [jvm]<br>open fun [setValue](index.md#-1882089003%2FFunctions%2F-267951372)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [stringExpression](index.md#510976662%2FFunctions%2F-267951372) | [jvm]<br>open fun [stringExpression](index.md#510976662%2FFunctions%2F-267951372)(p: ObservableValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): StringExpression |
| [toString](index.md#100326254%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](index.md#100326254%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.md#-1625174524%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbind](index.md#-1625174524%2FFunctions%2F-267951372)() |
| [unbindBidirectional](index.md#1978273438%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbindBidirectional](index.md#1978273438%2FFunctions%2F-267951372)(p: Property<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |

## Properties

| Name | Summary |
|---|---|
| [name](name.md) | [jvm]<br>private open var [name](name.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
