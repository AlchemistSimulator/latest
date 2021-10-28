//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](../index.md)/[NoAlignment](index.md)

# NoAlignment

[jvm]\
class [NoAlignment](index.md) : [AbstractGPSTimeAlignment](../-abstract-g-p-s-time-alignment/index.md)

No alignment is performed. If you have two traces, the first trace start with time = 2 and second point with time = 5, the second trace start with time = 4 and second point with time = 6, the result will be: - first trace start with time = 2 and second point with time = 5 - second trace start with time = 4 and second point with time = 6

## Constructors

| | |
|---|---|
| [NoAlignment](-no-alignment.md) | [jvm]<br>open fun [NoAlignment](-no-alignment.md)()<br>Default empty constructor, builds a NoAlignment with RETAIN_SINGLE_POINTS behavior for trace with single point. |

## Functions

| Name | Summary |
|---|---|
| [alignTime](../-abstract-g-p-s-time-alignment/align-time.md) | [jvm]<br>open fun [alignTime](../-abstract-g-p-s-time-alignment/align-time.md)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>[jvm]<br>abstract fun [alignTime](../-g-p-s-time-alignment/align-time.md)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>map trace with time to align |
