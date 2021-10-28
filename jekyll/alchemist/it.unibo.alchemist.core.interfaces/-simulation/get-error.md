---
title: getError
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[getError](get-error.html)



# getError



[jvm]\
abstract fun [getError](get-error.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)>



#### Return



an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the exception that made the simulation fail, or [empty](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html#empty--) in case the simulation is ongoing or has terminated successfully.




