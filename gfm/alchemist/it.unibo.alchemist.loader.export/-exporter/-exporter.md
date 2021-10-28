//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[Exporter](index.md)/[Exporter](-exporter.md)

# Exporter

[jvm]\
open fun [Exporter](-exporter.md)(target: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), space: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), header: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), columns: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Extractor](../-extractor/index.md)>)

## Parameters

jvm

| | |
|---|---|
| target | the target file |
| space | the sampling space, namely how many simulated time units the [Exporter](index.md) should log |
| header | a message to be inserted in the header of the file. |
| columns | the extractors to use |

#### Throws

| | |
|---|---|
| [java.io.FileNotFoundException](https://docs.oracle.com/javase/8/docs/api/java/io/FileNotFoundException.html) | if the file can not be opened for writing |
