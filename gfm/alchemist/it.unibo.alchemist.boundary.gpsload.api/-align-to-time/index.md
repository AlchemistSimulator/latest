//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](../index.md)/[AlignToTime](index.md)

# AlignToTime

[jvm]\
class [AlignToTime](index.md) : [AbstractGPSTimeAlignment](../-abstract-g-p-s-time-alignment/index.md)

Aligns the traces with the given time in seconds from Epoch. All points before such time will be discarded. All points after the provided time will be shifted back. Summarizing, the time that is provided represents in the real world the time zero of the simulation.

## Constructors

| | |
|---|---|
| [AlignToTime](-align-to-time.md) | [jvm]<br>open fun [AlignToTime](-align-to-time.md)(time: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), filterEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), exceptionForEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the time from which the traces should begin. |
| [AlignToTime](-align-to-time.md) | [jvm]<br>open fun [AlignToTime](-align-to-time.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), filterEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), exceptionForEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the time from which the traces should begin. |

## Functions

| Name | Summary |
|---|---|
| [alignTime](../-abstract-g-p-s-time-alignment/align-time.md) | [jvm]<br>open fun [alignTime](../-abstract-g-p-s-time-alignment/align-time.md)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>[jvm]<br>abstract fun [alignTime](../-g-p-s-time-alignment/align-time.md)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.md)><br>map trace with time to align |
