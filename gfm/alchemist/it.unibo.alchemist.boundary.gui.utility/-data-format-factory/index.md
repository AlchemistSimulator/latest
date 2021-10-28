//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.utility](../index.md)/[DataFormatFactory](index.md)

# DataFormatFactory

[jvm]\
class [DataFormatFactory](index.md)

Simple factory that returns the DataFormat for the specified class. 

 The DataFormat is cached to return only one per class and avoid {@code IllegalArgumentException: DataFormat 'xxx' already exists}.

## See also

jvm

| | |
|---|---|
| <a href="shorturl.at/AFUV0">Issue JDK-8118672</a> | [Issue JDK-8118672](shorturl.at/AFUV0) |

## Functions

| Name | Summary |
|---|---|
| [getDataFormat](get-data-format.md) | [jvm]<br>open fun [getDataFormat](get-data-format.md)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): DataFormat<br>open fun [getDataFormat](get-data-format.md)(object: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): DataFormat<br>Static DataFormat loader for the specified class. |
