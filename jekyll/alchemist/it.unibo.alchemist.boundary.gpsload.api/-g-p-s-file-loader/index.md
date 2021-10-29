---
title: GPSFileLoader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gpsload.api](../index.html)/[GPSFileLoader](index.html)



# GPSFileLoader



[jvm]\
interface [GPSFileLoader](index.html)

Strategy to read GPSTrace from file.



## Functions


| Name | Summary |
|---|---|
| [readTrace](read-trace.html) | [jvm]<br>abstract fun [readTrace](read-trace.html)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)><br>file with the trace request |
| [supportedExtensions](supported-extensions.html) | [jvm]<br>abstract fun [supportedExtensions](supported-extensions.html)(): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>all extension supported by this loader |


## Inheritors


| Name |
|---|
| [GPXLoader](../../it.unibo.alchemist.boundary.gpsload.impl/-g-p-x-loader/index.html) |

