---
title: Exporter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[Exporter](index.html)/[Exporter](-exporter.html)



# Exporter



[jvm]\
open fun [Exporter](-exporter.html)(target: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), space: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), header: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), columns: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Extractor](../-extractor/index.html)>)



## Parameters


jvm

| | |
|---|---|
| target | the target file |
| space | the sampling space, namely how many simulated time units the [Exporter](index.html) should log |
| header | a message to be inserted in the header of the file. |
| columns | the extractors to use |



#### Throws


| | |
|---|---|
| [java.io.FileNotFoundException](https://docs.oracle.com/javase/8/docs/api/java/io/FileNotFoundException.html) | if the file can not be opened for writing |



