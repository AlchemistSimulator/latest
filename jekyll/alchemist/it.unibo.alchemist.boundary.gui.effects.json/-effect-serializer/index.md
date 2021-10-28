---
title: EffectSerializer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectSerializer](index.html)



# EffectSerializer



[jvm]\
class [EffectSerializer](index.html)

Serialize Alchemist [effect groups](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from/to file in human readable format (JSON). 



 This class can be considered a clean boundary between Google Gson library and the needs of this project, providing methods to serialize and deserialize from JSON files instances of EffectGroup. 



 The GSON object used for serialization is statically updated at runtime with all available {@code TypeAdapters} and {@code RuntimeTypeAdapter}.



## See also


jvm

| | |
|---|---|
| com.google.gson.Gson |  |



## Functions


| Name | Summary |
|---|---|
| [effectFromFile](effect-from-file.html) | [jvm]<br>open fun <[P](effect-from-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectFromFile](effect-from-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>Get an [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) from the specified file. |
| [effectFromResources](effect-from-resources.html) | [jvm]<br>open fun <[P](effect-from-resources.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectFromResources](effect-from-resources.html)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>Get an [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) from the specified resource file. |
| [effectGroupsFromFile](effect-groups-from-file.html) | [jvm]<br>open fun <[P](effect-groups-from-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectGroupsFromFile](effect-groups-from-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>Get a list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from the specified file. |
| [effectGroupsFromResources](effect-groups-from-resources.html) | [jvm]<br>open fun <[P](effect-groups-from-resources.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectGroupsFromResources](effect-groups-from-resources.html)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>Get a list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from the specified resource file. |
| [effectGroupsToFile](effect-groups-to-file.html) | [jvm]<br>open fun <[P](effect-groups-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectGroupsToFile](effect-groups-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>>)<br>Write the given list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)s to the destination file. |
| [effectsFromFile](effects-from-file.html) | [jvm]<br>open fun <[P](effects-from-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectsFromFile](effects-from-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>Get an [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from the specified file. |
| [effectsFromResources](effects-from-resources.html) | [jvm]<br>open fun <[P](effects-from-resources.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectsFromResources](effects-from-resources.html)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>Get an [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from the specified resource file. |
| [effectsToFile](effects-to-file.html) | [jvm]<br>open fun <[P](effects-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectsToFile](effects-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>)<br>Write the given [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) to the destination file. |
| [effectToFile](effect-to-file.html) | [jvm]<br>open fun <[P](effect-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectToFile](effect-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>)<br>Write the given [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to the destination file. |
| [getGSON](get-g-s-o-n.html) | [jvm]<br>@Contract(pure = true)<br>@TestOnly()<br>open fun [getGSON](get-g-s-o-n.html)(): Gson<br>Returns the internal static instance of Gson object used for serialization. |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_CHARSET](-d-e-f-a-u-l-t_-c-h-a-r-s-e-t.html) | [jvm]<br>val [DEFAULT_CHARSET](-d-e-f-a-u-l-t_-c-h-a-r-s-e-t.html): [Charset](https://docs.oracle.com/javase/8/docs/api/java/nio/charset/Charset.html)<br>Default charset of serialized groups of effects. |
| [DEFAULT_EXTENSION](-d-e-f-a-u-l-t_-e-x-t-e-n-s-i-o-n.html) | [jvm]<br>val [DEFAULT_EXTENSION](-d-e-f-a-u-l-t_-e-x-t-e-n-s-i-o-n.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default extension of serialized groups of effects. |

