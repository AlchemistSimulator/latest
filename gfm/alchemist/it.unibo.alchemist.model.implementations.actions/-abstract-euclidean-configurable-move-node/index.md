//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractEuclideanConfigurableMoveNode](index.md)

# AbstractEuclideanConfigurableMoveNode

[jvm]\
abstract class [AbstractEuclideanConfigurableMoveNode](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, **node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **routing**: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[P](index.md)>, **target**: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](index.md)>, **speed**: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](index.md)>) : [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.md)<[T](index.md), [P](index.md)> 

It's an [AbstractConfigurableMoveNode](../-abstract-configurable-move-node/index.md) in the Euclidean world, which provides a default interpolatePositions that is accurate with respect to the target given and the current maximum walking distance.

## Constructors

| | |
|---|---|
| [AbstractEuclideanConfigurableMoveNode](-abstract-euclidean-configurable-move-node.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>> [AbstractEuclideanConfigurableMoveNode](-abstract-euclidean-configurable-move-node.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, routing: [RoutingStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-routing-strategy/index.md)<[P](index.md)>, target: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](index.md)>, speed: [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.md)<[P](index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md#1308842947%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[T](index.md)> |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](../-abstract-move-node/execute.md) | [jvm]<br>open override fun [execute](../-abstract-move-node/execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[T](index.md)> |
| [getContext](../-abstract-move-node/get-context.md) | [jvm]<br>override fun [getContext](../-abstract-move-node/get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentPosition](../-levy-walk/index.md#1706811851%2FFunctions%2F-267951372)(): [P](index.md) |
| [getCurrentRoute](../-levy-walk/index.md#-1147505500%2FFunctions%2F-267951372) | [jvm]<br>fun [getCurrentRoute](../-levy-walk/index.md#-1147505500%2FFunctions%2F-267951372)(): [Route](../../it.unibo.alchemist.model.interfaces/-route/index.md)<*> |
| [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372) | [jvm]<br>open fun [getEnvironment](../-levy-walk/index.md#-391547238%2FFunctions%2F-267951372)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.md) | [jvm]<br>override fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.md)(): [P](index.md) |
| [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)> |
| [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372) | [jvm]<br>fun [getNodePosition](../-levy-walk/index.md#1299827309%2FFunctions%2F-267951372)(p0: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>): [P](index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getTargetPoint](../-levy-walk/index.md#-1130383353%2FFunctions%2F-267951372) | [jvm]<br>fun [getTargetPoint](../-levy-walk/index.md#-1130383353%2FFunctions%2F-267951372)(): [P](index.md) |
| [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372) | [jvm]<br>fun [isAbsolute](../-levy-walk/index.md#9650230%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [resetRoute](../-levy-walk/index.md#1541249462%2FFunctions%2F-267951372) | [jvm]<br>fun [resetRoute](../-levy-walk/index.md#1541249462%2FFunctions%2F-267951372)() |
| [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-toggle-molecule-randomly/index.md#-330064727%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [T](index.md)) |
| [setTargetPoint](index.md#550794475%2FFunctions%2F-267951372) | [jvm]<br>fun [setTargetPoint](index.md#550794475%2FFunctions%2F-267951372)(p0: [P](index.md)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Inheritors

| Name |
|---|
| [GenericRandomWalker](../-generic-random-walker/index.md) |
