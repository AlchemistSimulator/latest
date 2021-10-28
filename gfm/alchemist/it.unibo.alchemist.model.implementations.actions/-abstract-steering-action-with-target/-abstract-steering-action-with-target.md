//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractSteeringActionWithTarget](index.md)/[AbstractSteeringActionWithTarget](-abstract-steering-action-with-target.md)

# AbstractSteeringActionWithTarget

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> [AbstractSteeringActionWithTarget](-abstract-steering-action-with-target.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>, target: [P](index.md))

[jvm]\
fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>> [AbstractSteeringActionWithTarget](-abstract-steering-action-with-target.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](index.md)>, pedestrian: [Pedestrian](../../it.unibo.alchemist.model.interfaces/-pedestrian/index.md)<[T](index.md), [P](index.md), [A](index.md)>, targetSelectionStrategy: [TargetSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](index.md)>)

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this action. |
| targetSelectionStrategy | strategy selecting the next target. |
