//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.config](../index.md)/[SimulationConfigImpl](index.md)

# SimulationConfigImpl

[jvm]\
class [SimulationConfigImpl](index.md) : [SimulationConfig](../-simulation-config/index.md)

[SimulationConfig](../-simulation-config/index.md) implementation.

## Constructors

| | |
|---|---|
| [SimulationConfigImpl](-simulation-config-impl.md) | [jvm]<br>open fun [SimulationConfigImpl](-simulation-config-impl.md)(variables: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)>)<br>Simulation's initialization variables |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getVariables](../-simulation-config/get-variables.md) | [jvm]<br>abstract fun [getVariables](../-simulation-config/get-variables.md)(): [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)><br>Simulation's inizialization variables |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [variables](variables.md) | [jvm]<br>private val [variables](variables.md): ImmutableMap<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)> |
