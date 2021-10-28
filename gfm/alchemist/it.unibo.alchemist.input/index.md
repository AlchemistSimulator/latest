//[alchemist](../../index.md)/[it.unibo.alchemist.input](index.md)

# Package it.unibo.alchemist.input

## Types

| Name | Summary |
|---|---|
| [ActionFromKey](-action-from-key/index.md) | [jvm]<br>enum [ActionFromKey](-action-from-key/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ActionFromKey](-action-from-key/index.md)> <br>Actions which can be bound to a key on the keyboard. |
| [Keybinds](-keybinds/index.md) | [jvm]<br>object [Keybinds](-keybinds/index.md)<br>Reads and writes a configuration of key bindings to a JSON file. |
| [KeybindsSerializer](-keybinds-serializer/index.md) | [jvm]<br>class [KeybindsSerializer](-keybinds-serializer/index.md) : JsonSerializer<[Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](-action-from-key/index.md), KeyCode>> <br>Serializer for keybinds that serializes [ActionFromKey](-action-from-key/index.md) by using the enum values' names instead of [ActionFromKey.toString](-action-from-key/to-string.md). |
