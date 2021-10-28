//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[SimulationConfig](index.md)

# SimulationConfig

[jvm]\
interface [SimulationConfig](index.md) : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

Simulation's configs for only one simulation.

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>abstract fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getVariables](get-variables.md) | [jvm]<br>abstract fun [getVariables](get-variables.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)><br>Simulation's inizialization variables |
| [hashCode](hash-code.md) | [jvm]<br>abstract fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Inheritors

| Name |
|---|
| [SimulationConfigImpl](../-simulation-config-impl/index.md) |
