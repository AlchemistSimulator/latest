---
title: AbstractEuclideanConfigurableMoveNode
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[AbstractEuclideanConfigurableMoveNode](index.html)



# AbstractEuclideanConfigurableMoveNode



[jvm]\
abstract class [AbstractEuclideanConfigurableMoveNode](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, **node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **routing**: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[P](index.html)>, **target**: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](index.html)>, **speed**: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](index.html)>) : [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.html)<[T](index.html), [P](index.html)> 

It's an [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.html) in the Euclidean world, which provides a default interpolatePositions that is accurate with respect to the target given and the current maximum walking distance.



## Constructors


| | |
|---|---|
| [AbstractEuclideanConfigurableMoveNode](-abstract-euclidean-configurable-move-node.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>> [AbstractEuclideanConfigurableMoveNode](-abstract-euclidean-configurable-move-node.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, routing: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.html)<[P](index.html)>, target: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](index.html)>, speed: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html#1308842947%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](index.html)> |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.html)> |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.html#1706811851%2FFunctions%2F-134779887)(): [P](index.html) |
| [getCurrentRoute](../-levy-walk/index.html#-1147505500%2FFunctions%2F-134779887) | [jvm]<br>fun [getCurrentRoute](../-levy-walk/index.html#-1147505500%2FFunctions%2F-134779887)(): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.html)<*> |
| [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.html#-391547238%2FFunctions%2F-134779887)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.html) | [jvm]<br>override fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.html)(): [P](index.html) |
| [getNode](../-camera-see/index.html#-1981508984%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-camera-see/index.html#-1981508984%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.html#1299827309%2FFunctions%2F-134779887)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>): [P](index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getTargetPoint](../-levy-walk/index.html#-1130383353%2FFunctions%2F-134779887) | [jvm]<br>fun [getTargetPoint](../-levy-walk/index.html#-1130383353%2FFunctions%2F-134779887)(): [P](index.html) |
| [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.html#9650230%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [resetRoute](../-levy-walk/index.html#1541249462%2FFunctions%2F-134779887) | [jvm]<br>fun [resetRoute](../-levy-walk/index.html#1541249462%2FFunctions%2F-134779887)() |
| [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.html#-330064727%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [T](index.html)) |
| [setTargetPoint](index.html#550794475%2FFunctions%2F-134779887) | [jvm]<br>fun [setTargetPoint](index.html#550794475%2FFunctions%2F-134779887)(p0: [P](index.html)) |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Inheritors


| Name |
|---|
| [GenericRandomWalker](../-generic-random-walker/index.html) |

