//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[LevyWalk](index.md)

# LevyWalk

[jvm]\
class [LevyWalk](index.md)<[T](index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **reaction**: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, **environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, **randomGenerator**: RandomGenerator, **speed**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **scale**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **shape**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [GenericRandomWalker](../-generic-random-walker/index.md)<[T](index.md)> 

Selects a target based on a random direction extracted from rng, and a random distance extracted from a ParetoDistribution of parameters scale and shape. Moves toward the targets at a constant speed and changes targets on collision.

## Constructors

| | |
|---|---|
| [LevyWalk](-levy-walk.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md)> [LevyWalk](-levy-walk.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, randomGenerator: RandomGenerator, speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), scale: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0, shape: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0) |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open override fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [LevyWalk](index.md)<[T](index.md)> |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](index.md#1706811851%2FFunctions%2F-267951372)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getCurrentRoute](index.md#-1147505500%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentRoute](index.md#-1147505500%2FFunctions%2F-267951372)(): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<*> |
| [getEnvironment](index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.md) | [jvm]<br>override fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.md)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNodePosition](index.md#1299827309%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](index.md#1299827309%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getTargetPoint](index.md#-1130383353%2FFunctions%2F-267951372) | [jvm]<br>fun [getTargetPoint](index.md#-1130383353%2FFunctions%2F-267951372)(): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md) |
| [isAbsolute](index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [resetRoute](index.md#1541249462%2FFunctions%2F-267951372) | [jvm]<br>fun [resetRoute](index.md#1541249462%2FFunctions%2F-267951372)() |
| [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [setTargetPoint](index.md#1485592096%2FFunctions%2F-267951372) | [jvm]<br>fun [setTargetPoint](index.md#1485592096%2FFunctions%2F-267951372)(p0: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
