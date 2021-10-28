---
title: setRealTime
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[GraphicalOutputMonitor](index.html)/[setRealTime](set-real-time.html)



# setRealTime



[jvm]\
abstract fun [setRealTime](set-real-time.html)(rt: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



If enabled, the monitor tries to synchronize the simulation time with the real time, slowing down the simulator if needed. If the simulation is slower than the real time, then the display refreshes fast enough to keep the default frame rate.



## Parameters


jvm

| | |
|---|---|
| rt | true for the real time mode |




