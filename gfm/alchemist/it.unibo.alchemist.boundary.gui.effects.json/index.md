//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](index.md)

# Package it.unibo.alchemist.boundary.gui.effects.json

[jvm]\
This package contains all the classes useful to save/load [effect groups](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) to/from file, in human-readable format (JSON).

## See also

jvm

| | |
|---|---|
| com.google.gson.Gson | Gson |

## Types

| Name | Summary |
|---|---|
| [ColorSerializationAdapter](-color-serialization-adapter/index.md) | [jvm]<br>open class [ColorSerializationAdapter](-color-serialization-adapter/index.md) : JsonSerializer<Color> , JsonDeserializer<Color> <br>This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize JavaFX Color objects. |
| [EffectGroupAdapter](-effect-group-adapter/index.md) | [jvm]<br>open class [EffectGroupAdapter](-effect-group-adapter/index.md)<[P](-effect-group-adapter/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> : JsonSerializer<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>> , JsonDeserializer<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>> <br>This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize a [EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) compatible class. |
| [EffectSerializer](-effect-serializer/index.md) | [jvm]<br>class [EffectSerializer](-effect-serializer/index.md)<br>Serialize Alchemist [effect groups](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from/to file in human readable format (JSON). |
