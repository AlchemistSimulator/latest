//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](../index.md)/[GPSFileLoader](index.md)

# GPSFileLoader

[jvm]\
interface [GPSFileLoader](index.md)

Strategy to read GPSTrace from file.

## Functions

| Name | Summary |
|---|---|
| [readTrace](read-trace.md) | [jvm]<br>abstract fun [readTrace](read-trace.md)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>file with the trace request |
| [supportedExtensions](supported-extensions.md) | [jvm]<br>abstract fun [supportedExtensions](supported-extensions.md)(): [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>all extension supported by this loader |

## Inheritors

| Name |
|---|
| [GPXLoader](../../it.unibo.alchemist.boundary.gpsload.impl/-g-p-x-loader/index.md) |
