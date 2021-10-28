---
title: AlignToSimulationTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gpsload.api](../index.html)/[AlignToSimulationTime](index.html)



# AlignToSimulationTime



[jvm]\
class [AlignToSimulationTime](index.html) : [AbstractGPSTimeAlignment](../-abstract-g-p-s-time-alignment/index.html)

Aligns all traces at the initial simulation time. If you have two traces, the first trace start with time = 2 and second point with time = 5, the second trace start with time = 4 and second point with time = 6, the result will be: - first trace start with time = 0 and second point with time = 3 - second trace start with time = 0 and second point with time = 2



## Constructors


| | |
|---|---|
| [AlignToSimulationTime](-align-to-simulation-time.html) | [jvm]<br>open fun [AlignToSimulationTime](-align-to-simulation-time.html)()<br>Default empty constructor, builds a AlignToSimulationTime with RETAIN_SINGLE_POINTS behavior for trace with single point. |


## Functions


| Name | Summary |
|---|---|
| [alignTime](../-abstract-g-p-s-time-alignment/align-time.html) | [jvm]<br>open fun [alignTime](../-abstract-g-p-s-time-alignment/align-time.html)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)><br>[jvm]<br>abstract fun [alignTime](../-g-p-s-time-alignment/align-time.html)(traces: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)>): ImmutableList<[GPSTrace](../../it.unibo.alchemist.model.interfaces/-g-p-s-trace/index.html)><br>map trace with time to align |

