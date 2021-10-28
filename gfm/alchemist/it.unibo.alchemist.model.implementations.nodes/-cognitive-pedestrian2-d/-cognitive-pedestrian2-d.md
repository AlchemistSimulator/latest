//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.nodes](../index.md)/[CognitivePedestrian2D](index.md)/[CognitivePedestrian2D](-cognitive-pedestrian2-d.md)

# CognitivePedestrian2D

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, age: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null)

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null)

[jvm]\

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](index.md)> [CognitivePedestrian2D](-cognitive-pedestrian2-d.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.md), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.md), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null, group: [PedestrianGroup2D](../../it.unibo.alchemist.model.interfaces/-pedestrian-group2-d/index.md)<[T](index.md)>? = null)

## Parameters

jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |
| danger | the molecule associated to danger in the environment. |
