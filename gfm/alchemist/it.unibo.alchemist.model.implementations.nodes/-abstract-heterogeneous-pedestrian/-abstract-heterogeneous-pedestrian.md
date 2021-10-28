//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[AbstractHeterogeneousPedestrian](index.md)/[AbstractHeterogeneousPedestrian](-abstract-heterogeneous-pedestrian.md)

# AbstractHeterogeneousPedestrian

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md), [P](index.md) : [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> [AbstractHeterogeneousPedestrian](-abstract-heterogeneous-pedestrian.md)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.md)<[T](index.md), [P](index.md), [A](index.md)>? = null)

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |
