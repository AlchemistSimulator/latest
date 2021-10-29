---
title: EffectGroupAdapter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectGroupAdapter](index.html)



# EffectGroupAdapter



[jvm]\
open class [EffectGroupAdapter](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>?> : JsonSerializer<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>> , JsonDeserializer<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>> 

This class should be registered in a com.google.gson.GsonBuilder to serialize and deserialize a [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) compatible class.



## Parameters


jvm

| | |
|---|---|
| <P> | The position type |



## Functions


| Name | Summary |
|---|---|
| [deserialize](deserialize.html) | [jvm]<br>open fun [deserialize](deserialize.html)(json: JsonElement, typeOfT: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonDeserializationContext): [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)> |
| [serialize](serialize.html) | [jvm]<br>open fun [serialize](serialize.html)(src: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>, typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonElement |

