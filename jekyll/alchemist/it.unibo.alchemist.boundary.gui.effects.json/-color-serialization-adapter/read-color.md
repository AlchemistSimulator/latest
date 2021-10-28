---
title: readColor
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects.json](../index.html)/[ColorSerializationAdapter](index.html)/[readColor](read-color.html)



# readColor



[jvm]\




@NotNull()



open fun [readColor](read-color.html)(stream: [ObjectInputStream](https://docs.oracle.com/javase/8/docs/api/java/io/ObjectInputStream.html)): @NotNull()Color



Generalized way to deserialize a JavaFX Color from a stream.



#### Return



the color to deserialize



## Parameters


jvm

| | |
|---|---|
| stream | the readObject() inputStream |



#### Throws


| | |
|---|---|
| [java.io.EOFException](https://docs.oracle.com/javase/8/docs/api/java/io/EOFException.html) | if the end of file is reached |
| [java.lang.ClassNotFoundException](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassNotFoundException.html) | if cannot find the class |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if other I/O error has occurred |


