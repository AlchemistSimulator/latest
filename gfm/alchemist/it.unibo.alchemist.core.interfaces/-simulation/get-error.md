//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[getError](get-error.md)

# getError

[jvm]\
abstract fun [getError](get-error.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)>

#### Return

an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the exception that made the simulation fail, or [empty](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html#empty--) in case the simulation is ongoing or has terminated successfully.
