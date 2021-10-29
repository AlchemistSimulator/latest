---
title: ColorSerializationAdapter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[ColorSerializationAdapter](index.html)



# ColorSerializationAdapter



[jvm]\
open class [ColorSerializationAdapter](index.html) : JsonSerializer<Color> , JsonDeserializer<Color> 

This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize JavaFX Color objects.



## Functions


| Name | Summary |
|---|---|
| [deserialize](deserialize.html) | [jvm]<br>open fun [deserialize](deserialize.html)(json: JsonElement, typeOfT: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonDeserializationContext): Color |
| [readColor](read-color.html) | [jvm]<br>@NotNull()<br>open fun [readColor](read-color.html)(stream: [ObjectInputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectInputStream.html)): @NotNull()Color<br>Generalized way to deserialize a JavaFX Color from a stream. |
| [serialize](serialize.html) | [jvm]<br>open fun [serialize](serialize.html)(src: Color, typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonElement |
| [writeColor](write-color.html) | [jvm]<br>open fun [writeColor](write-color.html)(stream: [ObjectOutputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectOutputStream.html), color: Color)<br>Generalized way to serialize JavaFX Color on a stream. |

