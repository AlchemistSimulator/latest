//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.util](../index.md)/[WorkingDirectory](index.md)

# WorkingDirectory

[jvm]\
class [WorkingDirectory](index.md) : [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)

Class that manage a temp local working directory.

## Constructors

| | |
|---|---|
| [WorkingDirectory](-working-directory.md) | [jvm]<br>open fun [WorkingDirectory](-working-directory.md)()<br>Create new local temp working directory. |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>open fun [close](close.md)() |
| [getDirectoryUrl](get-directory-url.md) | [jvm]<br>open fun [getDirectoryUrl](get-directory-url.md)(): [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)<br>Temp directory URL |
| [getFileAbsolutePath](get-file-absolute-path.md) | [jvm]<br>open fun [getFileAbsolutePath](get-file-absolute-path.md)(filename: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>File name |
| [getFileContent](get-file-content.md) | [jvm]<br>open fun [getFileContent](get-file-content.md)(filename: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Get folder's file content. |
| [writeFiles](write-files.md) | [jvm]<br>open fun [writeFiles](write-files.md)(files: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>>)<br>Write multiple files inside the directory. |
