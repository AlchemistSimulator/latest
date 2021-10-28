//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[EffectSerializer](index.md)/[getGSON](get-g-s-o-n.md)

# getGSON

[jvm]\

@Contract(pure = true)

@TestOnly()

open fun [getGSON](get-g-s-o-n.md)(): Gson

Returns the internal static instance of Gson object used for serialization. It includes all needed com.google.gson.TypeAdapters for [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md) and Properties serialization. 

 Useful for serialize related objects not directly managed by this class.

#### Return

the {@code Gson} object for serialization
