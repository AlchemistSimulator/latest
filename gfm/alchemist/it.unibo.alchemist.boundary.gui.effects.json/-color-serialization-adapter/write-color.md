//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects.json](../index.md)/[ColorSerializationAdapter](index.md)/[writeColor](write-color.md)

# writeColor

[jvm]\
open fun [writeColor](write-color.md)(stream: [ObjectOutputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectOutputStream.html), color: Color)

Generalized way to serialize JavaFX Color on a stream.

## Parameters

jvm

| | |
|---|---|
| stream | the writeObject() outputStream |
| color | the color to serialize |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if I/O errors occur while writing to the underlying stream |
