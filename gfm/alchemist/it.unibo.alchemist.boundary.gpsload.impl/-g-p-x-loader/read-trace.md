//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.impl](../index.md)/[GPXLoader](index.md)/[readTrace](read-trace.md)

# readTrace

[jvm]\
open fun [readTrace](read-trace.md)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>

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
