---
title: SimpleCharStream
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.expressions.parser](../index.html)/[SimpleCharStream](index.html)



# SimpleCharStream



[jvm]\
open class [SimpleCharStream](index.html)

An implementation of interface CharStream, where the stream is assumed to contain only ASCII characters (without unicode processing).



## Constructors


| | |
|---|---|
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Constructor. |
| [SimpleCharStream](-simple-char-stream.html) | [jvm]<br>open fun [SimpleCharStream](-simple-char-stream.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>Constructor. |


## Functions


| Name | Summary |
|---|---|
| [adjustBeginLineColumn](adjust-begin-line-column.html) | [jvm]<br>open fun [adjustBeginLineColumn](adjust-begin-line-column.html)(newLine: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), newCol: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Method to adjust line and column numbers for the start of a token. |
| [backup](backup.html) | [jvm]<br>open fun [backup](backup.html)(amount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Backup a number of characters. |
| [BeginToken](-begin-token.html) | [jvm]<br>open fun [BeginToken](-begin-token.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)<br>Start. |
| [Done](-done.html) | [jvm]<br>open fun [Done](-done.html)()<br>Reset buffer when finished. |
| [getBeginColumn](get-begin-column.html) | [jvm]<br>open fun [getBeginColumn](get-begin-column.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get token beginning column number. |
| [getBeginLine](get-begin-line.html) | [jvm]<br>open fun [getBeginLine](get-begin-line.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get token beginning line number. |
| [getEndColumn](get-end-column.html) | [jvm]<br>open fun [getEndColumn](get-end-column.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get token end column number. |
| [getEndLine](get-end-line.html) | [jvm]<br>open fun [getEndLine](get-end-line.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get token end line number. |
| [GetImage](-get-image.html) | [jvm]<br>open fun [GetImage](-get-image.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Get token literal value. |
| [GetSuffix](-get-suffix.html) | [jvm]<br>open fun [GetSuffix](-get-suffix.html)(len: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)><br>Get the suffix. |
| [readChar](read-char.html) | [jvm]<br>open fun [readChar](read-char.html)(): [Char](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char/index.html)<br>Read a character. |
| [ReInit](-re-init.html) | [jvm]<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html))<br>open fun [ReInit](-re-init.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html))<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [ReInit](-re-init.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [ReInit](-re-init.html)(dstream: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [ReInit](-re-init.html)(dstream: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), encoding: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), startline: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startcolumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), buffersize: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Reinitialise. |


## Properties


| Name | Summary |
|---|---|
| [bufpos](bufpos.html) | [jvm]<br>open val [bufpos](bufpos.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Position in buffer. |
| [column](column.html) | [jvm]<br>protected open val [column](column.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [line](line.html) | [jvm]<br>protected open val [line](line.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [staticFlag](static-flag.html) | [jvm]<br>val [staticFlag](static-flag.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Whether parser is static. |

