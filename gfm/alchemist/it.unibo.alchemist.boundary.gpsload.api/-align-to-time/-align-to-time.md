//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gpsload.api](../index.md)/[AlignToTime](index.md)/[AlignToTime](-align-to-time.md)

# AlignToTime

[jvm]\
open fun [AlignToTime](-align-to-time.md)(time: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), filterEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), exceptionForEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

open fun [AlignToTime](-align-to-time.md)(time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), filterEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), exceptionForEmpty: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

## Parameters

jvm

| | |
|---|---|
| time | the time from which the traces should begin. E.g., if you want all traces to begin at 2017-08-01 at 14:45:42 GMT, you should enter 1501598742 (seconds from Epoch). All points before such time will be discarded. All points after the provided time will be shifted back. Summarizing, the time that is provided represents in the real world the time zero of the simulation. |
| filterEmpty | if true filter empty traces |
| exceptionForEmpty | if true throw exception for empty traces |
