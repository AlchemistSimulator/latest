//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Status](index.md)

# Status

[jvm]\
enum [Status](index.md)

This enum represents the possible states in which a Simulation could be.

## Entries

| | |
|---|---|
| [INIT](-i-n-i-t/index.md) | [jvm]<br>[INIT](-i-n-i-t/index.md)<br>The simulation is being initialized. |
| [READY](-r-e-a-d-y/index.md) | [jvm]<br>[READY](-r-e-a-d-y/index.md)<br>The simulation is ready to be started. |
| [PAUSED](-p-a-u-s-e-d/index.md) | [jvm]<br>[PAUSED](-p-a-u-s-e-d/index.md)<br>The simulation is paused. |
| [RUNNING](-r-u-n-n-i-n-g/index.md) | [jvm]<br>[RUNNING](-r-u-n-n-i-n-g/index.md)<br>The simulation is currently running. |
| [TERMINATED](-t-e-r-m-i-n-a-t-e-d/index.md) | [jvm]<br>[TERMINATED](-t-e-r-m-i-n-a-t-e-d/index.md)<br>The simulation is stopped. |

## Functions

| Name | Summary |
|---|---|
| [isReachableFrom](is-reachable-from.md) | [jvm]<br>open fun [isReachableFrom](is-reachable-from.md)(s: [Status](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>the destination status |
| [valueOf](value-of.md) | [jvm]<br>open fun [valueOf](value-of.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Status](index.md) |
| [values](values.md) | [jvm]<br>open fun [values](values.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Status](index.md)> |
