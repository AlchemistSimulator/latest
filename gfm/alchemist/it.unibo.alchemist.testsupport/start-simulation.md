//[alchemist](../../index.md)/[it.unibo.alchemist.testsupport](index.md)/[startSimulation](start-simulation.md)

# startSimulation

[jvm]\
fun <[T](start-simulation.md), [P](start-simulation.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](start-simulation.md)>, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](start-simulation.md)>> [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](start-simulation.md), [P](start-simulation.md)>.[startSimulation](start-simulation.md)(initialized: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](start-simulation.md), [P](start-simulation.md)>) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { }, stepDone: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](start-simulation.md), [P](start-simulation.md)>, [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](start-simulation.md)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.md), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _, _ -> Unit }, finished: ([EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](start-simulation.md), [P](start-simulation.md)>, [Time](../it.unibo.alchemist.model.interfaces/-time/index.md), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) = { _, _, _ -> Unit }, steps: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 10000): [EuclideanEnvironment](../it.unibo.alchemist.model.interfaces/-euclidean-environment/index.md)<[T](start-simulation.md), [P](start-simulation.md)>

Run the simulation this environment owns.

## Parameters

jvm

| | |
|---|---|
| initialized | the lambda to execute when the simulation begins. |
| stepDone | the lambda to execute on each step of the simulation. |
| finished | the lambda to execute at the end of the simulation. |
| steps | the number of steps the simulation must execute. |
