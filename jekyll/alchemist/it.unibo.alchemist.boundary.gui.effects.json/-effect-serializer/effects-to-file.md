---
title: effectsToFile
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectSerializer](index.html)/[effectsToFile](effects-to-file.html)



# effectsToFile



[jvm]\
open fun <[P](effects-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectsToFile](effects-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>)



Write the given [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html) to the destination file.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |
| effectFile | Destination file |
| effects | Group of effects |



#### Throws


| | |
|---|---|
| com.google.gson.JsonIOException | If there was a problem writing to the writer |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | If the file exists but is a directory rather than a regular file, does not exist but cannot be created, cannot be opened for any other reason, or another I/O error occurs |



