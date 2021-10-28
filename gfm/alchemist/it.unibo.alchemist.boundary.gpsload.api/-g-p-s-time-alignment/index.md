//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](../index.md)/[GPSTimeAlignment](index.md)

# GPSTimeAlignment

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [GPSTimeAlignment](index.md)

Strategy to define how align the time of all trace.

## Functions

| Name | Summary |
|---|---|
| [alignTime](align-time.md) | [jvm]<br>abstract fun [alignTime](align-time.md)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>map trace with time to align |

## Inheritors

| Name |
|---|
| [AbstractGPSTimeAlignment](../-abstract-g-p-s-time-alignment/index.md) |
