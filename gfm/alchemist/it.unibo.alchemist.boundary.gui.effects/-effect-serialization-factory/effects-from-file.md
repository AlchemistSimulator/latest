//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectSerializationFactory](index.md)/[effectsFromFile](effects-from-file.md)

# effectsFromFile

[jvm]\
open fun [effectsFromFile](effects-from-file.md)(effectFile: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Effect](../-effect/index.md)>

Get a list of effects from the specified file. Try to deserialize a JSON file at first. If this operation is not successful (for the sake of backward compatibility) try to deserialize a binary file.

#### Return

List of the effects collected from the file

## Parameters

jvm

| | |
|---|---|
| effectFile | Source file |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | Exception in handling the file |
| [java.lang.ClassNotFoundException](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassNotFoundException.html) | In case the serialized binary object is not an effect |
