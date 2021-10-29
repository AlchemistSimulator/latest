---
title: KeybindsSerializer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.input](../index.html)/[KeybindsSerializer](index.html)



# KeybindsSerializer



[jvm]\
class [KeybindsSerializer](index.html) : JsonSerializer<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.html), KeyCode>> 

Serializer for keybinds that serializes [ActionFromKey](../-action-from-key/index.html) by using the enum values' names instead of [ActionFromKey.toString](../-action-from-key/to-string.html).



## Constructors


| | |
|---|---|
| [KeybindsSerializer](-keybinds-serializer.html) | [jvm]<br>fun [KeybindsSerializer](-keybinds-serializer.html)() |


## Functions


| Name | Summary |
|---|---|
| [serialize](serialize.html) | [jvm]<br>open override fun [serialize](serialize.html)(src: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.html), KeyCode>, typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonObject<br>{@inheritDoc}. |

