---
title: Keybinds
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.input](../index.html)/[Keybinds](index.html)



# Keybinds



[jvm]\
object [Keybinds](index.html)

Reads and writes a configuration of key bindings to a JSON file.



## Functions


| Name | Summary |
|---|---|
| [get](get.html) | [jvm]<br>operator fun [get](get.html)(action: [ActionFromKey](../-action-from-key/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<KeyCode><br>Retrieve the keys bound to a certain action. |
| [load](load.html) | [jvm]<br>fun [load](load.html)()<br>Load the binds from a file in the file system, reverting to classpath on failure. |
| [save](save.html) | [jvm]<br>fun [save](save.html)()<br>Write the binds to the file system. |
| [set](set.html) | [jvm]<br>operator fun [set](set.html)(action: [ActionFromKey](../-action-from-key/index.html), key: KeyCode)<br>Associate an action with a set of keys. |


## Properties


| Name | Summary |
|---|---|
| [config](config.html) | [jvm]<br>var [config](config.html): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[ActionFromKey](../-action-from-key/index.html), KeyCode><br>The currently loaded configuration. |

