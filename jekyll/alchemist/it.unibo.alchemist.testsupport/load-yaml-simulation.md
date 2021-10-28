---
title: loadYamlSimulation
---
//[alchemist](../../index.html)/[it.unibo.alchemist.testsupport](index.html)/[loadYamlSimulation](load-yaml-simulation.html)



# loadYamlSimulation



[jvm]\
fun <[T](load-yaml-simulation.html), [P](load-yaml-simulation.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](load-yaml-simulation.html)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](load-yaml-simulation.html)>> [loadYamlSimulation](load-yaml-simulation.html)(resource: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vars: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> = emptyMap()): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](load-yaml-simulation.html), [P](load-yaml-simulation.html)>



Loads a simulation from a YAML file.



## Parameters


jvm

| | |
|---|---|
| resource | the name of the file containing the simulation to load. |
| vars | a map specifying name-value bindings for the variables in this scenario. |




