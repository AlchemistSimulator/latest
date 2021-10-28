//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[ColorSerializationAdapter](index.md)

# ColorSerializationAdapter

[jvm]\
open class [ColorSerializationAdapter](index.md) : JsonSerializer<Color> , JsonDeserializer<Color> 

This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize JavaFX Color objects.

## Functions

| Name | Summary |
|---|---|
| [deserialize](deserialize.md) | [jvm]<br>open fun [deserialize](deserialize.md)(json: JsonElement, typeOfT: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonDeserializationContext): Color |
| [readColor](read-color.md) | [jvm]<br>@NotNull()<br>open fun [readColor](read-color.md)(stream: [ObjectInputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectInputStream.html)): @NotNull()Color<br>Generalized way to deserialize a JavaFX Color from a stream. |
| [serialize](serialize.md) | [jvm]<br>open fun [serialize](serialize.md)(src: Color, typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonElement |
| [writeColor](write-color.md) | [jvm]<br>open fun [writeColor](write-color.md)(stream: [ObjectOutputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectOutputStream.html), color: Color)<br>Generalized way to serialize JavaFX Color on a stream. |
