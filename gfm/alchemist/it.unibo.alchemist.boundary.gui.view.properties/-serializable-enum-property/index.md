//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[SerializableEnumProperty](index.md)

# SerializableEnumProperty

[jvm]\
open class [SerializableEnumProperty](index.md)<[T](index.md) : [Enum](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)<T>?> : ObjectPropertyBase<T> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

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
| [SerializableEnumProperty](-serializable-enum-property.md) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.md)()<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.md) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.md)(initialValue: T)<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.md) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>The constructor of {@code ObjectPropertyBase}. |
| [SerializableEnumProperty](-serializable-enum-property.md) | [jvm]<br>open fun [SerializableEnumProperty](-serializable-enum-property.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), initialValue: T)<br>The constructor of {@code ObjectPropertyBase}. |

## Functions

| Name | Summary |
|---|---|
| [addListener](index.md#-511801938%2FFunctions%2F-267951372) | [jvm]<br>open fun [addListener](index.md#-511801938%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [asString](index.md#-1664924783%2FFunctions%2F-267951372) | [jvm]<br>open fun [asString](index.md#-1664924783%2FFunctions%2F-267951372)(): StringBinding |
| [bind](index.md#1615523349%2FFunctions%2F-267951372) | [jvm]<br>open fun [bind](index.md#1615523349%2FFunctions%2F-267951372)(p: ObservableValue<out T>) |
| [bindBidirectional](index.md#-1943104152%2FFunctions%2F-267951372) | [jvm]<br>open fun [bindBidirectional](index.md#-1943104152%2FFunctions%2F-267951372)(p: Property<T>) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.md#1413784316%2FFunctions%2F-267951372) | [jvm]<br>open fun [get](index.md#1413784316%2FFunctions%2F-267951372)(): T |
| [getBean](get-bean.md) | [jvm]<br>open fun [getBean](get-bean.md)(): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>Getter method for unused field bean. |
| [getName](index.md#-1148459777%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getName](index.md#-1148459777%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [getValue](index.md#1553832377%2FFunctions%2F-267951372) | [jvm]<br>open fun [getValue](index.md#1553832377%2FFunctions%2F-267951372)(): T |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBound](index.md#-1318258914%2FFunctions%2F-267951372) | [jvm]<br>open fun [isBound](index.md#-1318258914%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEqualTo](index.md#-25141901%2FFunctions%2F-267951372) | [jvm]<br>open fun [isEqualTo](index.md#-25141901%2FFunctions%2F-267951372)(p: ObservableObjectValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): BooleanBinding |
| [isNotEqualTo](index.md#-1118016794%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotEqualTo](index.md#-1118016794%2FFunctions%2F-267951372)(p: ObservableObjectValue<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): BooleanBinding |
| [isNotNull](index.md#2110311638%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNotNull](index.md#2110311638%2FFunctions%2F-267951372)(): BooleanBinding |
| [isNull](index.md#-891486685%2FFunctions%2F-267951372) | [jvm]<br>open fun [isNull](index.md#-891486685%2FFunctions%2F-267951372)(): BooleanBinding |
| [objectExpression](index.md#634092268%2FFunctions%2F-267951372) | [jvm]<br>open fun <[T](index.md#634092268%2FFunctions%2F-267951372)> [objectExpression](index.md#634092268%2FFunctions%2F-267951372)(p: ObservableObjectValue<T>): ObjectExpression<T> |
| [removeListener](index.md#876250459%2FFunctions%2F-267951372) | [jvm]<br>open fun [removeListener](index.md#876250459%2FFunctions%2F-267951372)(p: InvalidationListener) |
| [set](index.md#230179262%2FFunctions%2F-267951372) | [jvm]<br>open fun [set](index.md#230179262%2FFunctions%2F-267951372)(p: T) |
| [setValue](index.md#1803825830%2FFunctions%2F-267951372) | [jvm]<br>open fun [setValue](index.md#1803825830%2FFunctions%2F-267951372)(p: T) |
| [toString](index.md#2128330268%2FFunctions%2F-267951372) | [jvm]<br>open fun [toString](index.md#2128330268%2FFunctions%2F-267951372)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [unbind](index.md#513246258%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbind](index.md#513246258%2FFunctions%2F-267951372)() |
| [unbindBidirectional](index.md#-595056977%2FFunctions%2F-267951372) | [jvm]<br>open fun [unbindBidirectional](index.md#-595056977%2FFunctions%2F-267951372)(p: Property<T>) |
| [values](values.md) | [jvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<T><br>Returns the elements of the enum class wrapped by this javafx.beans.property.Property. |

## Properties

| Name | Summary |
|---|---|
| [name](name.md) | [jvm]<br>private open var [name](name.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
