---
title: getGSON
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectSerializer](index.html)/[getGSON](get-g-s-o-n.html)



# getGSON



[jvm]\




@Contract(pure = true)



@TestOnly()



open fun [getGSON](get-g-s-o-n.html)(): Gson



Returns the internal static instance of Gson object used for serialization. It includes all needed com.google.gson.TypeAdapters for [Effects](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) and Properties serialization. 



 Useful for serialize related objects not directly managed by this class.



#### Return



the {@code Gson} object for serialization




