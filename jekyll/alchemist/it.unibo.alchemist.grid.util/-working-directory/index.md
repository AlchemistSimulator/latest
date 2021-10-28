---
title: WorkingDirectory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.util](../index.html)/[WorkingDirectory](index.html)



# WorkingDirectory



[jvm]\
class [WorkingDirectory](index.html) : [AutoCloseable](https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html)

Class that manage a temp local working directory.



## Constructors


| | |
|---|---|
| [WorkingDirectory](-working-directory.html) | [jvm]<br>open fun [WorkingDirectory](-working-directory.html)()<br>Create new local temp working directory. |


## Functions


| Name | Summary |
|---|---|
| [close](close.html) | [jvm]<br>open fun [close](close.html)() |
| [getDirectoryUrl](get-directory-url.html) | [jvm]<br>open fun [getDirectoryUrl](get-directory-url.html)(): [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)<br>Temp directory URL |
| [getFileAbsolutePath](get-file-absolute-path.html) | [jvm]<br>open fun [getFileAbsolutePath](get-file-absolute-path.html)(filename: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>File name |
| [getFileContent](get-file-content.html) | [jvm]<br>open fun [getFileContent](get-file-content.html)(filename: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Get folder's file content. |
| [writeFiles](write-files.html) | [jvm]<br>open fun [writeFiles](write-files.html)(files: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>>)<br>Write multiple files inside the directory. |

