//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[EffectSerializer](index.md)/[effectGroupsFromResources](effect-groups-from-resources.md)

# effectGroupsFromResources

[jvm]\
open fun <[P](effect-groups-from-resources.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>?> [effectGroupsFromResources](effect-groups-from-resources.md)(resource: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>>

Get a list of [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) from the specified resource file. It tries to deserialize a JSON file.

#### Return

List of the effect groups collected from the file

## Parameters

jvm

| | |
|---|---|
| <P> | the position type |
| resource | resource file |

#### Throws

| | |
|---|---|
| [java.io.FileNotFoundException](https://docs.oracle.com/javase/8/docs/api/java/io/FileNotFoundException.html) | If the file does not exist, is a directory rather than a regular file, or for some other reason cannot be opened for reading |
| com.google.gson.JsonIOException | If there was a problem reading from the Reader |
| com.google.gson.JsonSyntaxException | If JSON is not a valid representation for an object of type |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | If some other I/O error occurs |
