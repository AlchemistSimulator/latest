---
title: it.unibo.alchemist.input
---
//[alchemist](../../index.html)/[it.unibo.alchemist.input](index.html)



# Package it.unibo.alchemist.input



## Types


| Name | Summary |
|---|---|
| [ActionFromKey](-action-from-key/index.html) | [jvm]<br>enum [ActionFromKey](-action-from-key/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionFromKey](-action-from-key/index.html)> <br>Actions which can be bound to a key on the keyboard. |
| [Keybinds](-keybinds/index.html) | [jvm]<br>object [Keybinds](-keybinds/index.html)<br>Reads and writes a configuration of key bindings to a JSON file. |
| [KeybindsSerializer](-keybinds-serializer/index.html) | [jvm]<br>class [KeybindsSerializer](-keybinds-serializer/index.html) : JsonSerializer<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](-action-from-key/index.html), KeyCode>> <br>Serializer for keybinds that serializes [ActionFromKey](-action-from-key/index.html) by using the enum values' names instead of [ActionFromKey.toString](-action-from-key/to-string.html). |

