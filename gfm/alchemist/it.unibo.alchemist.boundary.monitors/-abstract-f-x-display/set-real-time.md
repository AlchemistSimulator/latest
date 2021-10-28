//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.monitors](../index.md)/[AbstractFXDisplay](index.md)/[setRealTime](set-real-time.md)

# setRealTime

[jvm]\
open override fun [setRealTime](set-real-time.md)(realTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. If the simulation is slower than the real time, then the display refreshes fast enough to keep the default frame rate.

## Parameters

jvm

| | |
|---|---|
| realTime | true for the real time mode |
