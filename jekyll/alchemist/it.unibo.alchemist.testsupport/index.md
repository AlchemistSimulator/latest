---
title: it.unibo.alchemist.testsupport
---
//[alchemist](../../index.html)/[it.unibo.alchemist.testsupport](index.html)



# Package it.unibo.alchemist.testsupport



## Functions


| Name | Summary |
|---|---|
| [loadYamlSimulation](load-yaml-simulation.html) | [jvm]<br>fun <[T](load-yaml-simulation.html), [P](load-yaml-simulation.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](load-yaml-simulation.html)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](load-yaml-simulation.html)>> [loadYamlSimulation](load-yaml-simulation.html)(resource: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vars: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> = emptyMap()): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](load-yaml-simulation.html), [P](load-yaml-simulation.html)><br>Loads a simulation from a YAML file. |
| [startSimulation](start-simulation.html) | [jvm]<br>fun <[T](start-simulation.html), [P](start-simulation.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](start-simulation.html)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](start-simulation.html)>> [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>.[startSimulation](start-simulation.html)(initialized: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { }, stepDone: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>, [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](start-simulation.html)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.html), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _, _ -> Unit }, finished: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.html), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _ -> Unit }, steps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 10000): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)><br>Run the simulation this environment owns. |

