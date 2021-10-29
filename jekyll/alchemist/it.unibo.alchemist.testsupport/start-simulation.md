---
title: startSimulation
---
//[alchemist](../../index.html)/[it.unibo.alchemist.testsupport](index.html)/[startSimulation](start-simulation.html)



# startSimulation



[jvm]\
fun <[T](start-simulation.html), [P](start-simulation.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](start-simulation.html)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](start-simulation.html)>> [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>.[startSimulation](start-simulation.html)(initialized: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { }, stepDone: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>, [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](start-simulation.html)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.html), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _, _ -> Unit }, finished: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.html), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _ -> Unit }, steps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 10000): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.html)<[T](start-simulation.html), [P](start-simulation.html)>



Run the simulation this environment owns.



## Parameters


jvm

| | |
|---|---|
| initialized | the lambda to execute when the simulation begins. |
| stepDone | the lambda to execute on each step of the simulation. |
| finished | the lambda to execute at the end of the simulation. |
| steps | the number of steps the simulation must execute. |




