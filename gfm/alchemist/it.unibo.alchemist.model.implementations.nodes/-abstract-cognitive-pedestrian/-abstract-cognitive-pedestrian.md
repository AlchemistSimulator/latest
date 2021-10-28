//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractCognitivePedestrian](index.md)/[AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.md)

# AbstractCognitivePedestrian

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.md)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>? = null, cognitive: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.md)? = null)

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |
| danger | the molecule associated to danger in the environment. |
