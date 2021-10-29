---
title: AbstractCognitivePedestrian
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.nodes](../index.html)/[AbstractCognitivePedestrian](index.html)/[AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.html)



# AbstractCognitivePedestrian



[jvm]\




@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>> [AbstractCognitivePedestrian](-abstract-cognitive-pedestrian.html)(environment: [PhysicsEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics-environment/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)>, randomGenerator: RandomGenerator, age: [Age](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-age/index.html), gender: [Gender](../../it.unibo.alchemist.model.cognitiveagents.impact.individual/-gender/index.html), danger: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null, group: [PedestrianGroup](../../it.unibo.alchemist.model.interfaces/-pedestrian-group/index.html)<[T](index.html), [P](index.html), [A](index.html)>? = null, cognitive: [CognitiveModel](../../it.unibo.alchemist.model.cognitiveagents/-cognitive-model/index.html)? = null)



## Parameters


jvm

| | |
|---|---|
| environment | the environment inside which this pedestrian moves. |
| randomGenerator | the simulation {@link RandomGenerator}. |
| age | the age of this pedestrian. |
| gender | the gender of this pedestrian |
| danger | the molecule associated to danger in the environment. |




