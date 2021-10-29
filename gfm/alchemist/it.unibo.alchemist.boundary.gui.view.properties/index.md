//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](index.md)

# Package it.unibo.alchemist.boundary.gui.view.properties

[jvm]\
This package contains new JavaFX Properties specifically written to be [java.io.Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html) and to be used as [Effects](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) properties. 

 This choice makes the binding process with JavaFX GUI components (like the [ effect tuner](../it.unibo.alchemist.boundary.gui.controller/-effect-properties-controller/index.md) drawer) much more easy.

## Types

| Name | Summary |
|---|---|
| [PropertyFactory](-property-factory/index.md) | [jvm]<br>class [PropertyFactory](-property-factory/index.md)<br>Factory for custom {@code Property}. |
| [PropertyTypeAdapter](-property-type-adapter/index.md) | [jvm]<br>interface [PropertyTypeAdapter](-property-type-adapter/index.md)<[T](-property-type-adapter/index.md) : Property<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : JsonSerializer<T> , JsonDeserializer<T> <br>This interface lets implement classes for JavaFX custom property serialization. |
| [RangedDoubleProperty](-ranged-double-property/index.md) | [jvm]<br>class [RangedDoubleProperty](-ranged-double-property/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **initialValue**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **lowerBound**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **upperBound**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : DoublePropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>This DoubleProperty is designed to have a range for the wrapped value and to be serializable. |
| [RangedIntegerProperty](-ranged-integer-property/index.md) | [jvm]<br>open class [RangedIntegerProperty](-ranged-integer-property/index.md) : IntegerPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>This javafx.beans.property.IntegerProperty is designed to have a range for the wrapped value and to be serializable. |
| [SerializableBooleanProperty](-serializable-boolean-property/index.md) | [jvm]<br>open class [SerializableBooleanProperty](-serializable-boolean-property/index.md) : BooleanPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>javafx.beans.property.SimpleBooleanProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html). |
| [SerializableEnumProperty](-serializable-enum-property/index.md) | [jvm]<br>open class [SerializableEnumProperty](-serializable-enum-property/index.md)<[T](-serializable-enum-property/index.md) : [Enum](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)<T>?> : ObjectPropertyBase<T> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>javafx.beans.property.Property designed to wrap an [enum](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html). |
| [SerializableStringProperty](-serializable-string-property/index.md) | [jvm]<br>open class [SerializableStringProperty](-serializable-string-property/index.md) : StringPropertyBase, [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>javafx.beans.property.SimpleStringProperty that implements also [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html). |
