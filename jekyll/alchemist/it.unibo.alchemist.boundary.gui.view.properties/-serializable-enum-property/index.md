---
title: SerializableEnumProperty
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[SerializableEnumProperty](index.html)



# SerializableEnumProperty



[jvm]\
open class [SerializableEnumProperty](index.html)<[T](index.html) : [Enum](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)<[T](../-property-type-adapter/index.html)>?> : ObjectPropertyBase<[T](../-property-type-adapter/index.html)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

javafx.beans.property.Property designed to wrap an [enum](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html). 



 It is based on {@code ObjectPropertyBase} and is {@code Serializable}.



## Parameters


jvm

| | |
|---|---|
| <T> | the enumeration wrapped |



## Constructors


| | |
|---|---|
| [SerializableEnumProperty](-serializable-enum-property.html) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.html)()<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.html) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.html)(initialValue: [T](../-property-type-adapter/index.html))<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.html) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.html) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: [T](../-property-type-adapter/index.html))<br>The constructor of {@code ObjectPropertyBase}. |


## Functions


| Name | Summary |
|---|---|
| [addListener](index.html#-511801938%2FFunctions%2F-134779887) | [jvm]<br>open fun [addListener](index.html#-511801938%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [asString](index.html#-1664924783%2FFunctions%2F-134779887) | [jvm]<br>open fun [asString](index.html#-1664924783%2FFunctions%2F-134779887)(): StringBinding |
| [bind](index.html#1615523349%2FFunctions%2F-134779887) | [jvm]<br>open fun [bind](index.html#1615523349%2FFunctions%2F-134779887)(p: ObservableValue<out [T](../-property-type-adapter/index.html)>) |
| [bindBidirectional](index.html#-1943104152%2FFunctions%2F-134779887) | [jvm]<br>open fun [bindBidirectional](index.html#-1943104152%2FFunctions%2F-134779887)(p: Property<[T](../-property-type-adapter/index.html)>) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.html#1413784316%2FFunctions%2F-134779887) | [jvm]<br>open fun [get](index.html#1413784316%2FFunctions%2F-134779887)(): [T](../-property-type-adapter/index.html) |
| [getBean](get-bean.html) | [jvm]<br>open fun [getBean](get-bean.html)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](index.html#-1148459777%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getName](index.html#-1148459777%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getValue](index.html#1553832377%2FFunctions%2F-134779887) | [jvm]<br>open fun [getValue](index.html#1553832377%2FFunctions%2F-134779887)(): [T](../-property-type-adapter/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.html#-1318258914%2FFunctions%2F-134779887) | [jvm]<br>open fun [isBound](index.html#-1318258914%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEqualTo](index.html#-25141901%2FFunctions%2F-134779887) | [jvm]<br>open fun [isEqualTo](index.html#-25141901%2FFunctions%2F-134779887)(p: ObservableObjectValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): BooleanBinding |
| [isNotEqualTo](index.html#-1118016794%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotEqualTo](index.html#-1118016794%2FFunctions%2F-134779887)(p: ObservableObjectValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): BooleanBinding |
| [isNotNull](index.html#2110311638%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNotNull](index.html#2110311638%2FFunctions%2F-134779887)(): BooleanBinding |
| [isNull](index.html#-891486685%2FFunctions%2F-134779887) | [jvm]<br>open fun [isNull](index.html#-891486685%2FFunctions%2F-134779887)(): BooleanBinding |
| [objectExpression](index.html#634092268%2FFunctions%2F-134779887) | [jvm]<br>open fun <[T](index.html#634092268%2FFunctions%2F-134779887)> [objectExpression](index.html#634092268%2FFunctions%2F-134779887)(p: ObservableObjectValue<[T](../-property-type-adapter/index.html)>): ObjectExpression<[T](../-property-type-adapter/index.html)> |
| [removeListener](index.html#876250459%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeListener](index.html#876250459%2FFunctions%2F-134779887)(p: InvalidationListener) |
| [set](index.html#230179262%2FFunctions%2F-134779887) | [jvm]<br>open fun [set](index.html#230179262%2FFunctions%2F-134779887)(p: [T](../-property-type-adapter/index.html)) |
| [setValue](index.html#1803825830%2FFunctions%2F-134779887) | [jvm]<br>open fun [setValue](index.html#1803825830%2FFunctions%2F-134779887)(p: [T](../-property-type-adapter/index.html)) |
| [toString](index.html#2128330268%2FFunctions%2F-134779887) | [jvm]<br>open fun [toString](index.html#2128330268%2FFunctions%2F-134779887)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.html#513246258%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbind](index.html#513246258%2FFunctions%2F-134779887)() |
| [unbindBidirectional](index.html#-595056977%2FFunctions%2F-134779887) | [jvm]<br>open fun [unbindBidirectional](index.html#-595056977%2FFunctions%2F-134779887)(p: Property<[T](../-property-type-adapter/index.html)>) |
| [values](values.html) | [jvm]<br>open fun [values](values.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../-property-type-adapter/index.html)><br>Returns the elements of the enum class wrapped by this javafx.beans.property.Property. |


## Properties


| Name | Summary |
|---|---|
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

