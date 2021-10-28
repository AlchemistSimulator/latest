//[alchemist](../../../index.md)/[it.unibo.alchemist.input](../index.md)/[Keybinds](index.md)

# Keybinds

[jvm]\
object [Keybinds](index.md)

Reads and writes a configuration of key bindings to a JSON file.

## Functions

| Name | Summary |
|---|---|
| [get](get.md) | [jvm]<br>operator fun [get](get.md)(action: [ActionFromKey](../-action-from-key/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<KeyCode><br>Retrieve the keys bound to a certain action. |
| [load](load.md) | [jvm]<br>fun [load](load.md)()<br>Load the binds from a file in the file system, reverting to classpath on failure. |
| [save](save.md) | [jvm]<br>fun [save](save.md)()<br>Write the binds to the file system. |
| [set](set.md) | [jvm]<br>operator fun [set](set.md)(action: [ActionFromKey](../-action-from-key/index.md), key: KeyCode)<br>Associate an action with a set of keys. |

## Properties

| Name | Summary |
|---|---|
| [config](config.md) | [jvm]<br>var [config](config.md): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.md), KeyCode><br>The currently loaded configuration. |
