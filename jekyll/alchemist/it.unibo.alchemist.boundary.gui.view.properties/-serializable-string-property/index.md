---
title: SerializableStringProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[SerializableStringProperty](index.html)



# SerializableStringProperty



[jvm]\
open class [SerializableStringProperty](index.html) : StringPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

javafx.beans.property.SimpleStringProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).



## Constructors


| | |
|---|---|
| [SerializableStringProperty](-serializable-string-property.html) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.html)()<br>The constructor of {@code SimpleStringProperty}. |
| [SerializableStringProperty](-serializable-string-property.html) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.html)(initialValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleStringProperty}. |
| [SerializableStringProperty](-serializable-string-property.html) | [jvm]<br>open fun [SerializableStringProperty](-serializable-string-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code SimpleStringProperty}. |


## Functions


| Name | Summary |
|---|---|
| [addListener](index.html#-741023232%2FFunctions%2F-134779887) | [jvm]<br>open fun [addListener](index.html#-741023232%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [bind](index.html#1367372508%2FFunctions%2F-134779887) | [jvm]<br>open fun [bind](index.html#1367372508%2FFunctions%2F-134779887)(p: ObservableValue<out [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [bindBidirectional](index.html#-253756859%2FFunctions%2F-134779887) | [jvm]<br>open fun [bindBidirectional](index.html#-253756859%2FFunctions%2F-134779887)(p: Property<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |
| [concat](index.html#1381068703%2FFunctions%2F-134779887) | [jvm]<br>open fun [concat](index.html#1381068703%2FFunctions%2F-134779887)(p: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): StringExpression |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.html#-1896285590%2FFunctions%2F-134779887) | [jvm]<br>open fun [get](index.html#-1896285590%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>abstract fun [get](index.html#-692577270%2FFunctions%2F-134779887)(): [T](../-property-type-adapter/index.html) |
| [getBean](get-bean.html) | [jvm]<br>open fun [getBean](get-bean.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getName](../-serializable-enum-property/index.html#-1148459777%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getTypeAdapter](get-type-adapter.html) | [jvm]<br>open fun [getTypeAdapter](get-type-adapter.html)(): [PropertyTypeAdapter](../-property-type-adapter/index.html)<[SerializableStringProperty](index.html)><br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code SerializableStringProperty}. |
| [getValue](index.html#-584588405%2FFunctions%2F-134779887) | [jvm]<br>open fun [getValue](index.html#-584588405%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>abstract fun [getValue](../-serializable-boolean-property/index.html#414617374%2FFunctions%2F-134779887)(): [T](../-property-type-adapter/index.html) |
| [getValueSafe](index.html#1835836798%2FFunctions%2F-134779887) | [jvm]<br>fun [getValueSafe](index.html#1835836798%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [greaterThan](index.html#351412510%2FFunctions%2F-134779887) | [jvm]<br>open fun [greaterThan](index.html#351412510%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [greaterThanOrEqualTo](index.html#923048218%2FFunctions%2F-134779887) | [jvm]<br>open fun [greaterThanOrEqualTo](index.html#923048218%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.html#1110173580%2FFunctions%2F-134779887) | [jvm]<br>open fun [isBound](index.html#1110173580%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEmpty](index.html#-1787983215%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEmpty](index.html#-1787983215%2FFunctions%2F-134779887)(): BooleanBinding |
| [isEqualTo](index.html#623749268%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEqualTo](index.html#623749268%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [isEqualToIgnoreCase](index.html#1467134482%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEqualToIgnoreCase](index.html#1467134482%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [isNotEmpty](index.html#1746828194%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEmpty](index.html#1746828194%2FFunctions%2F-134779887)(): BooleanBinding |
| [isNotEqualTo](index.html#1853469797%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEqualTo](index.html#1853469797%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [isNotEqualToIgnoreCase](index.html#-735908701%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEqualToIgnoreCase](index.html#-735908701%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [isNotNull](index.html#243776836%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotNull](index.html#243776836%2FFunctions%2F-134779887)(): BooleanBinding |
| [isNull](index.html#-424438667%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNull](index.html#-424438667%2FFunctions%2F-134779887)(): BooleanBinding |
| [length](index.html#-575804160%2FFunctions%2F-134779887) | [jvm]<br>open fun [length](index.html#-575804160%2FFunctions%2F-134779887)(): IntegerBinding |
| [lessThan](index.html#1905668049%2FFunctions%2F-134779887) | [jvm]<br>open fun [lessThan](index.html#1905668049%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [lessThanOrEqualTo](index.html#-1502977081%2FFunctions%2F-134779887) | [jvm]<br>open fun [lessThanOrEqualTo](index.html#-1502977081%2FFunctions%2F-134779887)(p: ObservableStringValue): BooleanBinding |
| [removeListener](index.html#1142681545%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeListener](index.html#1142681545%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [set](index.html#412778713%2FFunctions%2F-134779887) | [jvm]<br>open fun [set](index.html#412778713%2FFunctions%2F-134779887)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [setValue](index.html#-1882089003%2FFunctions%2F-134779887) | [jvm]<br>open fun [setValue](index.html#-1882089003%2FFunctions%2F-134779887)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)) |
| [stringExpression](index.html#510976662%2FFunctions%2F-134779887) | [jvm]<br>open fun [stringExpression](index.html#510976662%2FFunctions%2F-134779887)(p: ObservableValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): StringExpression |
| [toString](index.html#100326254%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#100326254%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.html#-1625174524%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbind](index.html#-1625174524%2FFunctions%2F-134779887)() |
| [unbindBidirectional](index.html#1978273438%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbindBidirectional](index.html#1978273438%2FFunctions%2F-134779887)(p: Property<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)>) |


## Properties


| Name | Summary |
|---|---|
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

