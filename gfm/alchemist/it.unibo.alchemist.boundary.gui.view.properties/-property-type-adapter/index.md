//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view.properties](../index.md)/[PropertyTypeAdapter](index.md)

# PropertyTypeAdapter

[jvm]\
interface [PropertyTypeAdapter](index.md)<[T](index.md) : Property<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : JsonSerializer<[T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)> , JsonDeserializer<[T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)> 

This interface lets implement classes for JavaFX custom property serialization.

## Parameters

jvm

| | |
|---|---|
| <T> | the Property type |

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [jvm]<br>abstract fun [deserialize](deserialize.md)(json: JsonElement, typeOfT: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonDeserializationContext): [T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md) |
| [serialize](serialize.md) | [jvm]<br>abstract fun [serialize](serialize.md)(src: [T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md), typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonElement |

## Properties

| Name | Summary |
|---|---|
| [BEAN](-b-e-a-n.md) | [jvm]<br>val [BEAN](-b-e-a-n.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "bean". |
| [NAME](-n-a-m-e.md) | [jvm]<br>val [NAME](-n-a-m-e.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "name". |
| [VALUE](-v-a-l-u-e.md) | [jvm]<br>val [VALUE](-v-a-l-u-e.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "value". |
