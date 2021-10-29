//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[EffectSerializer](index.md)

# EffectSerializer

[jvm]\
class [EffectSerializer](index.md)

Serialize Alchemist [effect groups](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from/to file in human readable format (JSON). 

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
| [effectFromFile](effect-from-file.md) | [jvm]<br>open fun <[P](effect-from-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectFromFile](effect-from-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Get an [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) from the specified file. |
| [effectFromResources](effect-from-resources.md) | [jvm]<br>open fun <[P](effect-from-resources.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectFromResources](effect-from-resources.md)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Get an [Effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) from the specified resource file. |
| [effectGroupsFromFile](effect-groups-from-file.md) | [jvm]<br>open fun <[P](effect-groups-from-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectGroupsFromFile](effect-groups-from-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>><br>Get a list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from the specified file. |
| [effectGroupsFromResources](effect-groups-from-resources.md) | [jvm]<br>open fun <[P](effect-groups-from-resources.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectGroupsFromResources](effect-groups-from-resources.md)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>><br>Get a list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from the specified resource file. |
| [effectGroupsToFile](effect-groups-to-file.md) | [jvm]<br>open fun <[P](effect-groups-to-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectGroupsToFile](effect-groups-to-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>>)<br>Write the given list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)s to the destination file. |
| [effectsFromFile](effects-from-file.md) | [jvm]<br>open fun <[P](effects-from-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectsFromFile](effects-from-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Get an [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from the specified file. |
| [effectsFromResources](effects-from-resources.md) | [jvm]<br>open fun <[P](effects-from-resources.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectsFromResources](effects-from-resources.md)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Get an [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from the specified resource file. |
| [effectsToFile](effects-to-file.md) | [jvm]<br>open fun <[P](effects-to-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectsToFile](effects-to-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>)<br>Write the given [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) to the destination file. |
| [effectToFile](effect-to-file.md) | [jvm]<br>open fun <[P](effect-to-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectToFile](effect-to-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>)<br>Write the given [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) to the destination file. |
| [getGSON](get-g-s-o-n.md) | [jvm]<br>@Contract(pure = true)<br>@TestOnly()<br>open fun [getGSON](get-g-s-o-n.md)(): Gson<br>Returns the internal static instance of Gson object used for serialization. |

## Properties

| Name | Summary |
|---|---|
| [DEFAULT_CHARSET](-d-e-f-a-u-l-t_-c-h-a-r-s-e-t.md) | [jvm]<br>val [DEFAULT_CHARSET](-d-e-f-a-u-l-t_-c-h-a-r-s-e-t.md): [Charset](https://docs.oracle.com/javase/8/docs/api/java/nio/charset/Charset.html)<br>Default charset of serialized groups of effects. |
| [DEFAULT_EXTENSION](-d-e-f-a-u-l-t_-e-x-t-e-n-s-i-o-n.md) | [jvm]<br>val [DEFAULT_EXTENSION](-d-e-f-a-u-l-t_-e-x-t-e-n-s-i-o-n.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Default extension of serialized groups of effects. |
