//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[EffectSerializer](index.md)/[effectsToFile](effects-to-file.md)

# effectsToFile

[jvm]\
open fun <[P](effects-to-file.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [effectsToFile](effects-to-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html), effects: [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>)

Write the given [EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md) to the destination file.

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
