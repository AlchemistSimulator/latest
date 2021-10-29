---
title: effectToFile
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectSerializer](index.html)/[effectToFile](effect-to-file.html)



# effectToFile



[jvm]\
open fun <[P](effect-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../-effect-group-adapter/index.html)>?> [effectToFile](effect-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../-effect-group-adapter/index.html)>)



Write the given [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html) to the destination file.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |
| effectFile | Destination file |
| effect | Effect |



#### Throws


| | |
|---|---|
| com.google.gson.JsonIOException | If there was a problem writing to the writer |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | If the file exists but is a directory rather than a regular file, does not exist but cannot be created, cannot be opened for any other reason, or another I/O error occurs |



