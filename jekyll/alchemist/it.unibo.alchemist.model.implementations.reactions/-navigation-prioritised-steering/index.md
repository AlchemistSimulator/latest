---
title: NavigationPrioritisedSteering
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[NavigationPrioritisedSteering](index.html)



# NavigationPrioritisedSteering



[jvm]\
open class [NavigationPrioritisedSteering](index.html)<[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**env**: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, **pedestrian**: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, **timeDistribution**: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>, **toleranceAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SteeringBehavior](../-steering-behavior/index.html)<[T](index.html)> 

A [SteeringBehavior](../-steering-behavior/index.html) using [SinglePrevalent](../../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-single-prevalent/index.html) steering strategy and accepting a collection of actions containing a single [NavigationAction2D](../../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887), which is used as the prevalent one.



## Parameters


jvm

| | |
|---|---|
| T | concentration type |
| N | type of nodes of the environment's graph. |



## Constructors


| | |
|---|---|
| [NavigationPrioritisedSteering](-navigation-prioritised-steering.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun <[T](index.html), [N](index.html) : [ConvexPolygon](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)> [NavigationPrioritisedSteering](-navigation-prioritised-steering.html)(env: [Euclidean2DEnvironmentWithGraph](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](index.html), [N](index.html), *>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>, toleranceAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Math.toDegrees(SinglePrevalent.DEFAULT_TOLERANCE_ANGLE), alpha: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = SinglePrevalent.DEFAULT_ALPHA)<br>concentration type |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-1772000845%2FFunctions%2F-134779887) | [jvm]<br>fun [addInboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-1772000845%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-2022076396%2FFunctions%2F-134779887) | [jvm]<br>fun [addOutboundDependency](../-navigation-prioritised-steering-with-physics/index.html#-2022076396%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [canExecute](../-abstract-reaction/can-execute.html) | [jvm]<br>open override fun [canExecute](../-abstract-reaction/can-execute.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [cloneOnNewNode](../-steering-behavior/clone-on-new-node.html) | [jvm]<br>open override fun [cloneOnNewNode](../-steering-behavior/clone-on-new-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>?, currentTime: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)?): [SteeringBehavior](../-steering-behavior/index.html)<[T](index.html)> |
| [compareTo](../-navigation-prioritised-steering-with-physics/index.html#588180668%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [compareTo](../-navigation-prioritised-steering-with-physics/index.html#588180668%2FFunctions%2F-134779887)(other: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](../-navigation-prioritised-steering-with-physics/index.html#-267299839%2FFunctions%2F-134779887) | [jvm]<br>operator override fun [equals](../-navigation-prioritised-steering-with-physics/index.html#-267299839%2FFunctions%2F-134779887)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [execute](../-steering-behavior/execute.html) | [jvm]<br>open override fun [execute](../-steering-behavior/execute.html)() |
| [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getActions](../-navigation-prioritised-steering-with-physics/index.html#13515737%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)>> |
| [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getConditions](../-navigation-prioritised-steering-with-physics/index.html#-184159508%2FFunctions%2F-134779887)(): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)>> |
| [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html) | [jvm]<br>override fun [getInboundDependencies](../-abstract-reaction/get-inbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getInputContext](../-abstract-reaction/get-input-context.html) | [jvm]<br>override fun [getInputContext](../-abstract-reaction/get-input-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887) | [jvm]<br>override fun [getNode](../-navigation-prioritised-steering-with-physics/index.html#-1244046302%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-reaction/get-outbound-dependencies.html)(): ListSet<[Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getOutputContext](../-abstract-reaction/get-output-context.html) | [jvm]<br>override fun [getOutputContext](../-abstract-reaction/get-output-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getRate](../-steering-behavior/get-rate.html) | [jvm]<br>open override fun [getRate](../-steering-behavior/get-rate.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRateAsString](../-navigation-prioritised-steering-with-physics/index.html#-166271391%2FFunctions%2F-134779887) | [jvm]<br>open fun [getRateAsString](../-navigation-prioritised-steering-with-physics/index.html#-166271391%2FFunctions%2F-134779887)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getReactionName](../-navigation-prioritised-steering-with-physics/index.html#494389008%2FFunctions%2F-134779887) | [jvm]<br>open fun [getReactionName](../-navigation-prioritised-steering-with-physics/index.html#494389008%2FFunctions%2F-134779887)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTau](../-abstract-reaction/get-tau.html) | [jvm]<br>override fun [getTau](../-abstract-reaction/get-tau.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html) |
| [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887) | [jvm]<br>override fun [getTimeDistribution](../-navigation-prioritised-steering-with-physics/index.html#2053953683%2FFunctions%2F-134779887)(): [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)> |
| [hashCode](../-abstract-reaction/hash-code.html) | [jvm]<br>override fun [hashCode](../-abstract-reaction/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [initializationComplete](../-navigation-prioritised-steering-with-physics/index.html#496764034%2FFunctions%2F-134779887) | [jvm]<br>open override fun [initializationComplete](../-navigation-prioritised-steering-with-physics/index.html#496764034%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) |
| [makeClone](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) | [jvm]<br>open fun <[R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) : [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>> [makeClone](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887)(p0: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887)>): [R](../-navigation-prioritised-steering-with-physics/index.html#1151787077%2FFunctions%2F-134779887) |
| [setActions](../-navigation-prioritised-steering-with-physics/index.html#1557798850%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setActions](../-navigation-prioritised-steering-with-physics/index.html#1557798850%2FFunctions%2F-134779887)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)>>) |
| [setConditions](../-navigation-prioritised-steering-with-physics/index.html#-1302498472%2FFunctions%2F-134779887) | [jvm]<br>open override fun [setConditions](../-navigation-prioritised-steering-with-physics/index.html#-1302498472%2FFunctions%2F-134779887)(p0: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)>>) |
| [setInputContext](../-navigation-prioritised-steering-with-physics/index.html#-1096973185%2FFunctions%2F-134779887) | [jvm]<br>fun [setInputContext](../-navigation-prioritised-steering-with-physics/index.html#-1096973185%2FFunctions%2F-134779887)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)) |
| [setOutputContext](../-navigation-prioritised-steering-with-physics/index.html#-1034313602%2FFunctions%2F-134779887) | [jvm]<br>fun [setOutputContext](../-navigation-prioritised-steering-with-physics/index.html#-1034313602%2FFunctions%2F-134779887)(p0: [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)) |
| [steerActions](../-steering-behavior/steer-actions.html) | [jvm]<br>fun [steerActions](../-steering-behavior/steer-actions.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>><br>The list of steering actions in this reaction. |
| [toString](../-abstract-reaction/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-reaction/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [update](../-navigation-prioritised-steering-with-physics/index.html#-1541973436%2FFunctions%2F-134779887) | [jvm]<br>override fun [update](../-navigation-prioritised-steering-with-physics/index.html#-1541973436%2FFunctions%2F-134779887)(p0: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), p1: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), p2: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), *>) |


## Properties


| Name | Summary |
|---|---|
| [steerStrategy](index.html#1436630772%2FProperties%2F-134779887) | [jvm]<br>open val [steerStrategy](index.html#1436630772%2FProperties%2F-134779887): [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>    the strategy used to combine steering actions. |


## Inheritors


| Name |
|---|
| [NavigationPrioritisedSteeringWithPhysics](../-navigation-prioritised-steering-with-physics/index.html) |
