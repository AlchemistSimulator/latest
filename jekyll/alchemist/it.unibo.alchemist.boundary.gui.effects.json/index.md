---
title: it.unibo.alchemist.boundary.gui.effects.json
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](index.html)



# Package it.unibo.alchemist.boundary.gui.effects.json



[jvm]\
This package contains all the classes useful to save/load [effect groups](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) to/from file, in human-readable format (JSON).



## See also


jvm

| | |
|---|---|
| com.google.gson.Gson | Gson |



## Types


| Name | Summary |
|---|---|
| [ColorSerializationAdapter](-color-serialization-adapter/index.html) | [jvm]<br>open class [ColorSerializationAdapter](-color-serialization-adapter/index.html) : JsonSerializer<Color> , JsonDeserializer<Color> <br>This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize JavaFX Color objects. |
| [EffectGroupAdapter](-effect-group-adapter/index.html) | [jvm]<br>open class [EffectGroupAdapter](-effect-group-adapter/index.html)<[P](-effect-group-adapter/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : JsonSerializer<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>> , JsonDeserializer<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>> <br>This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize a [EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) compatible class. |
| [EffectSerializer](-effect-serializer/index.html) | [jvm]<br>class [EffectSerializer](-effect-serializer/index.html)<br>Serialize Alchemist [effect groups](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) from/to file in human readable format (JSON). |

