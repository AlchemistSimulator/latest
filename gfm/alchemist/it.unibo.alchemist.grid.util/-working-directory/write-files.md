//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.util](../index.md)/[WorkingDirectory](index.md)/[writeFiles](write-files.md)

# writeFiles

[jvm]\
open fun [writeFiles](write-files.md)(files: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>>)

Write multiple files inside the directory.

## Parameters

jvm

| | |
|---|---|
| files | A map with relative paths + files names as keys and file contents as values. |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of an I/O error |
