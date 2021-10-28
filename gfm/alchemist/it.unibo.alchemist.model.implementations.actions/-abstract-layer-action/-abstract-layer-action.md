//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractLayerAction](index.md)/[AbstractLayerAction](-abstract-layer-action.md)

# AbstractLayerAction

[jvm]\
fun [AbstractLayerAction](-abstract-layer-action.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)>, targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which the pedestrian moves. |
| reaction | the reaction which executes this action. |
| pedestrian | the owner of this action. |
| targetMolecule | the {@link Molecule} you want to know the concentration in the different positions of the environment. |
