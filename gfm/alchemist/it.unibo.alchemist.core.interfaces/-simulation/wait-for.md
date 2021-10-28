//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[waitFor](wait-for.md)

# waitFor

[jvm]\
abstract fun [waitFor](wait-for.md)(s: [Status](../-status/index.md), timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), timeunit: [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)): [Status](../-status/index.md)

Suspends the caller until the simulation reaches the selected [Status](../-status/index.md) or the timeout ends. Please note that waiting for a status does not mean that every [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md) will already be notified of the update.

#### Return

the status of the Simulation at the end of the wait

## Parameters

jvm

| | |
|---|---|
| s | The [Status](../-status/index.md) the simulation should reach before returning from this method |
| timeout | The maximum lapse of time the caller wants to wait before being resumed |
| timeunit | The [TimeUnit](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html) used to define "timeout" |
