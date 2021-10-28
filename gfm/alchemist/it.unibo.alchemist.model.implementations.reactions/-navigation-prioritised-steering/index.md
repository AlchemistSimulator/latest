//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[NavigationPrioritisedSteering](index.md)

# NavigationPrioritisedSteering

[jvm]\
open class [NavigationPrioritisedSteering](index.md)<[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**env**: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), *>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, **timeDistribution**: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)>, **toleranceAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SteeringBehavior](../-steering-behavior/index.md)<[T](index.md)> 

A [SteeringBehavior](../-steering-behavior/index.md) using [SinglePrevalent](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-single-prevalent/index.md) steering strategy and accepting a collection of actions containing a single [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.md#-517309547%2FClasslikes%2F-267951372), which is used as the prevalent one.

## Parameters

jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |

## Constructors

| | |
|---|---|
| [NavigationPrioritisedSteering](-navigation-prioritised-steering.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.md), [N](index.md) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.md)> [NavigationPrioritisedSteering](-navigation-prioritised-steering.md)(env: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.md)<*, [T](index.md), [N](index.md), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Math.toDegrees(SinglePrevalent.DEFAULT_TOLERANCE_ANGLE), alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = SinglePrevalent.DEFAULT_ALPHA)<br>concentration type |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.md#-1772000845%2FFunctions%2F-267951372) | [jvm]<br>fun [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.md#-1772000845%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.md#-2022076396%2FFunctions%2F-267951372) | [jvm]<br>fun [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.md#-2022076396%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [canExecute](../-abstract-reaction/can-execute.md) | [jvm]<br>open override fun [canExecute](../-abstract-reaction/can-execute.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](../-steering-behavior/clone-on-new-node.md) | [jvm]<br>open override fun [cloneOnNewNode](../-steering-behavior/clone-on-new-node.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>?, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)?): [SteeringBehavior](../-steering-behavior/index.md)<[T](index.md)> |
| [compareTo](../-navigation-prioritised-steering-with-physics/index.md#588180668%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [compareTo](../-navigation-prioritised-steering-with-physics/index.md#588180668%2FFunctions%2F-267951372)(other: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-navigation-prioritised-steering-with-physics/index.md#-267299839%2FFunctions%2F-267951372) | [jvm]<br>operator override fun [equals](../-navigation-prioritised-steering-with-physics/index.md#-267299839%2FFunctions%2F-267951372)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](../-steering-behavior/execute.md) | [jvm]<br>open override fun [execute](../-steering-behavior/execute.md)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.md#13515737%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getActions](../-navigation-prioritised-steering-with-physics/index.md#13515737%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.md#-184159508%2FFunctions%2F-267951372) | [jvm]<br>open override fun [getConditions](../-navigation-prioritised-steering-with-physics/index.md#-184159508%2FFunctions%2F-267951372)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](index.md)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.md) | [jvm]<br>override fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getInputContext](../-abstract-reaction/get-input-context.md) | [jvm]<br>override fun [getInputContext](../-abstract-reaction/get-input-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.md#-1244046302%2FFunctions%2F-267951372) | [jvm]<br>override fun [getNode](../-navigation-prioritised-steering-with-physics/index.md#-1244046302%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.md)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getOutputContext](../-abstract-reaction/get-output-context.md) | [jvm]<br>override fun [getOutputContext](../-abstract-reaction/get-output-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getRate](../-steering-behavior/get-rate.md) | [jvm]<br>open override fun [getRate](../-steering-behavior/get-rate.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateAsString](../-navigation-prioritised-steering-with-physics/index.md#-166271391%2FFunctions%2F-267951372) | [jvm]<br>open fun [getRateAsString](../-navigation-prioritised-steering-with-physics/index.md#-166271391%2FFunctions%2F-267951372)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getReactionName](../-navigation-prioritised-steering-with-physics/index.md#494389008%2FFunctions%2F-267951372) | [jvm]<br>open fun [getReactionName](../-navigation-prioritised-steering-with-physics/index.md#494389008%2FFunctions%2F-267951372)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTau](../-abstract-reaction/get-tau.md) | [jvm]<br>override fun [getTau](../-abstract-reaction/get-tau.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.md#2053953683%2FFunctions%2F-267951372) | [jvm]<br>override fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.md#2053953683%2FFunctions%2F-267951372)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)> |
| [hashCode](../-abstract-reaction/hash-code.md) | [jvm]<br>override fun [hashCode](../-abstract-reaction/hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-navigation-prioritised-steering-with-physics/index.md#496764034%2FFunctions%2F-267951372) | [jvm]<br>open override fun [initializationComplete](../-navigation-prioritised-steering-with-physics/index.md#496764034%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>) |
| [makeClone](../-navigation-prioritised-steering-with-physics/index.md#1151787077%2FFunctions%2F-267951372) | [jvm]<br>open fun <[R](../-navigation-prioritised-steering-with-physics/index.md#1151787077%2FFunctions%2F-267951372) : [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>> [makeClone](../-navigation-prioritised-steering-with-physics/index.md#1151787077%2FFunctions%2F-267951372)(p0: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[R](../-navigation-prioritised-steering-with-physics/index.md#1151787077%2FFunctions%2F-267951372)>): [R](../-navigation-prioritised-steering-with-physics/index.md#1151787077%2FFunctions%2F-267951372) |
| [setActions](../-navigation-prioritised-steering-with-physics/index.md#1557798850%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setActions](../-navigation-prioritised-steering-with-physics/index.md#1557798850%2FFunctions%2F-267951372)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)>>) |
| [setConditions](../-navigation-prioritised-steering-with-physics/index.md#-1302498472%2FFunctions%2F-267951372) | [jvm]<br>open override fun [setConditions](../-navigation-prioritised-steering-with-physics/index.md#-1302498472%2FFunctions%2F-267951372)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.md)<[T](index.md)>>) |
| [setInputContext](../-navigation-prioritised-steering-with-physics/index.md#-1096973185%2FFunctions%2F-267951372) | [jvm]<br>fun [setInputContext](../-navigation-prioritised-steering-with-physics/index.md#-1096973185%2FFunctions%2F-267951372)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)) |
| [setOutputContext](../-navigation-prioritised-steering-with-physics/index.md#-1034313602%2FFunctions%2F-267951372) | [jvm]<br>fun [setOutputContext](../-navigation-prioritised-steering-with-physics/index.md#-1034313602%2FFunctions%2F-267951372)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md)) |
| [steerActions](../-steering-behavior/steer-actions.md) | [jvm]<br>fun [steerActions](../-steering-behavior/steer-actions.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>><br>The list of steering actions in this reaction. |
| [toString](../-abstract-reaction/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-reaction/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](../-navigation-prioritised-steering-with-physics/index.md#-1541973436%2FFunctions%2F-267951372) | [jvm]<br>override fun [update](../-navigation-prioritised-steering-with-physics/index.md#-1541973436%2FFunctions%2F-267951372)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), *>) |

## Properties

| Name | Summary |
|---|---|
| [steerStrategy](index.md#1436630772%2FProperties%2F-267951372) | [jvm]<br>open val [steerStrategy](index.md#1436630772%2FProperties%2F-267951372): [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>    the strategy used to combine steering actions. |

## Inheritors

| Name |
|---|
| [NavigationPrioritisedSteeringWithPhysics](../-navigation-prioritised-steering-with-physics/index.md) |
