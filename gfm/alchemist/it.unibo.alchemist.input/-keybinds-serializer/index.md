//[alchemist](../../../index.md)/[it.unibo.alchemist.input](../index.md)/[KeybindsSerializer](index.md)

# KeybindsSerializer

[jvm]\
class [KeybindsSerializer](index.md) : JsonSerializer<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.md), KeyCode>> 

Serializer for keybinds that serializes [ActionFromKey](../-action-from-key/index.md) by using the enum values' names instead of [ActionFromKey.toString](../-action-from-key/to-string.md).

## Constructors

| | |
|---|---|
| [KeybindsSerializer](-keybinds-serializer.md) | [jvm]<br>fun [KeybindsSerializer](-keybinds-serializer.md)() |

## Functions

| Name | Summary |
|---|---|
| [serialize](serialize.md) | [jvm]<br>open override fun [serialize](serialize.md)(src: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.md), KeyCode>, typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonObject<br>{@inheritDoc}. |
