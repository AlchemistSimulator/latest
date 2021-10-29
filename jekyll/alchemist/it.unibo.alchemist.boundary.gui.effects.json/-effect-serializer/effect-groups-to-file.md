---
title: effectGroupsToFile
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[EffectSerializer](index.html)/[effectGroupsToFile](effect-groups-to-file.html)



# effectGroupsToFile



[jvm]\
open fun <[P](effect-groups-to-file.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> [effectGroupsToFile](effect-groups-to-file.html)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>>)



Write the given list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)s to the destination file.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |
| effectFile | Destination file |
| effects | List of group of effects |



#### Throws


| | |
|---|---|
| com.google.gson.JsonIOException | If there was a problem writing to the writer |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | If the file exists but is a directory rather than a regular file, does not exist but cannot be created, cannot be opened for any other reason, or another I/O error occurs |



