---
title: readTrace
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gpsload.api](../index.html)/[GPSFileLoader](index.html)/[readTrace](read-trace.html)



# readTrace



[jvm]\
abstract fun [readTrace](read-trace.html)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)>



#### Return



GPSTrace readed



## Parameters


jvm

| | |
|---|---|
| url | file with the trace request |



#### Throws


| | |
|---|---|
| org.openstreetmap.osmosis.osmbinary.file.FileFormatException | file format not valid |
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | in case of I/O errors |



