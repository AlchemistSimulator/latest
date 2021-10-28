//[alchemist](../../index.md)/[it.unibo.alchemist.testsupport](index.md)/[loadYamlSimulation](load-yaml-simulation.md)

# loadYamlSimulation

[jvm]\
fun <[T](load-yaml-simulation.md), [P](load-yaml-simulation.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](load-yaml-simulation.md)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](load-yaml-simulation.md)>> [loadYamlSimulation](load-yaml-simulation.md)(resource: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vars: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> = emptyMap()): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](load-yaml-simulation.md), [P](load-yaml-simulation.md)>

Loads a simulation from a YAML file.

## Parameters

jvm

| | |
|---|---|
| resource | the name of the file containing the simulation to load. |
| vars | a map specifying name-value bindings for the variables in this scenario. |
