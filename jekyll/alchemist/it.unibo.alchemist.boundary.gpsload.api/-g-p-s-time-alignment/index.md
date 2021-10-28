---
title: GPSTimeAlignment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gpsload.api](../index.html)/[GPSTimeAlignment](index.html)



# GPSTimeAlignment



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [GPSTimeAlignment](index.html)

Strategy to define how align the time of all trace.



## Functions


| Name | Summary |
|---|---|
| [alignTime](align-time.html) | [jvm]<br>abstract fun [alignTime](align-time.html)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)><br>map trace with time to align |


## Inheritors


| Name |
|---|
| [AbstractGPSTimeAlignment](../-abstract-g-p-s-time-alignment/index.html) |

