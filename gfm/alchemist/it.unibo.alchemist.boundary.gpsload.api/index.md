//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](index.md)

# Package it.unibo.alchemist.boundary.gpsload.api

## Types

| Name | Summary |
|---|---|
| [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md) | [jvm]<br>abstract class [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md) : [GPSTimeAlignment](-g-p-s-time-alignment/index.md) |
| [AlignToFirstTrace](-align-to-first-trace/index.md) | [jvm]<br>class [AlignToFirstTrace](-align-to-first-trace/index.md) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md)<br>Aligns all traces at the start time of the first trace. |
| [AlignToSimulationTime](-align-to-simulation-time/index.md) | [jvm]<br>class [AlignToSimulationTime](-align-to-simulation-time/index.md) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md)<br>Aligns all traces at the initial simulation time. |
| [AlignToTime](-align-to-time/index.md) | [jvm]<br>class [AlignToTime](-align-to-time/index.md) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md)<br>Aligns the traces with the given time in seconds from Epoch. |
| [GPSFileLoader](-g-p-s-file-loader/index.md) | [jvm]<br>interface [GPSFileLoader](-g-p-s-file-loader/index.md)<br>Strategy to read GPSTrace from file. |
| [GPSTimeAlignment](-g-p-s-time-alignment/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [GPSTimeAlignment](-g-p-s-time-alignment/index.md)<br>Strategy to define how align the time of all trace. |
| [NoAlignment](-no-alignment/index.md) | [jvm]<br>class [NoAlignment](-no-alignment/index.md) : [AbstractGPSTimeAlignment](-abstract-g-p-s-time-alignment/index.md)<br>No alignment is performed. |
