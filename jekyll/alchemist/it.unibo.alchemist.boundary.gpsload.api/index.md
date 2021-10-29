---
title: it.unibo.alchemist.boundary.gpsload.api
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.gpsload.api](index.html)



# Package it.unibo.alchemist.boundary.gpsload.api



## Types


| Name | Summary |
|---|---|
| [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html) | [jvm]<br>abstract class [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html) : [GPSTimeAlignment](-g-p-s-time-alignment/index.html) |
| [AlignToFirstTrace](-align-to-first-trace/index.html) | [jvm]<br>class [AlignToFirstTrace](-align-to-first-trace/index.html) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html)<br>Aligns all traces at the start time of the first trace. |
| [AlignToSimulationTime](-align-to-simulation-time/index.html) | [jvm]<br>class [AlignToSimulationTime](-align-to-simulation-time/index.html) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html)<br>Aligns all traces at the initial simulation time. |
| [AlignToTime](-align-to-time/index.html) | [jvm]<br>class [AlignToTime](-align-to-time/index.html) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html)<br>Aligns the traces with the given time in seconds from Epoch. |
| [GPSFileLoader](-g-p-s-file-loader/index.html) | [jvm]<br>interface [GPSFileLoader](-g-p-s-file-loader/index.html)<br>Strategy to read GPSTrace from file. |
| [GPSTimeAlignment](-g-p-s-time-alignment/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [GPSTimeAlignment](-g-p-s-time-alignment/index.html)<br>Strategy to define how align the time of all trace. |
| [NoAlignment](-no-alignment/index.html) | [jvm]<br>class [NoAlignment](-no-alignment/index.html) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.html)<br>No alignment is performed. |

