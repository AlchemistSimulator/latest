---
title: SimulationConfig
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.config](../index.html)/[SimulationConfig](index.html)



# SimulationConfig



[jvm]\
interface [SimulationConfig](index.html) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Simulation's configs for only one simulation.



## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>abstract fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getVariables](get-variables.html) | [jvm]<br>abstract fun [getVariables](get-variables.html)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)><br>Simulation's inizialization variables |
| [hashCode](hash-code.html) | [jvm]<br>abstract fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Inheritors


| Name |
|---|
| [SimulationConfigImpl](../-simulation-config-impl/index.html) |

