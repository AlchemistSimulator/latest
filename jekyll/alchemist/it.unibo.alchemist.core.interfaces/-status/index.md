---
title: Status
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Status](index.html)



# Status



[jvm]\
enum [Status](index.html)

This enum represents the possible states in which a Simulation could be.



## Entries


| | |
|---|---|
| [INIT](-i-n-i-t/index.html) | [jvm]<br>[INIT](-i-n-i-t/index.html)<br>The simulation is being initialized. |
| [READY](-r-e-a-d-y/index.html) | [jvm]<br>[READY](-r-e-a-d-y/index.html)<br>The simulation is ready to be started. |
| [PAUSED](-p-a-u-s-e-d/index.html) | [jvm]<br>[PAUSED](-p-a-u-s-e-d/index.html)<br>The simulation is paused. |
| [RUNNING](-r-u-n-n-i-n-g/index.html) | [jvm]<br>[RUNNING](-r-u-n-n-i-n-g/index.html)<br>The simulation is currently running. |
| [TERMINATED](-t-e-r-m-i-n-a-t-e-d/index.html) | [jvm]<br>[TERMINATED](-t-e-r-m-i-n-a-t-e-d/index.html)<br>The simulation is stopped. |


## Functions


| Name | Summary |
|---|---|
| [isReachableFrom](is-reachable-from.html) | [jvm]<br>open fun [isReachableFrom](is-reachable-from.html)(s: [Status](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the destination status |
| [valueOf](value-of.html) | [jvm]<br>open fun [valueOf](value-of.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Status](index.html) |
| [values](values.html) | [jvm]<br>open fun [values](values.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Status](index.html)> |

