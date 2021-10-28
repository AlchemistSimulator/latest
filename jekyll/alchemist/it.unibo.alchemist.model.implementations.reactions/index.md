---
title: it.unibo.alchemist.model.implementations.reactions
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.reactions](index.html)



# Package it.unibo.alchemist.model.implementations.reactions



## Types


| Name | Summary |
|---|---|
| [AbstractReaction](-abstract-reaction/index.html) | [jvm]<br>abstract class [AbstractReaction](-abstract-reaction/index.html)<[T](-abstract-reaction/index.html)> : [Reaction](../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> <br>The type which describes the concentration of a molecule This class offers a partial implementation of Reaction. |
| [BiochemicalReaction](-biochemical-reaction/index.html) | [jvm]<br>class [BiochemicalReaction](-biochemical-reaction/index.html) : [ChemicalReaction](-chemical-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> <br>A biochemical Reaction. |
| [BiochemicalReactionBuilder](-biochemical-reaction-builder/index.html) | [jvm]<br>open class [BiochemicalReactionBuilder](-biochemical-reaction-builder/index.html)<[P](-biochemical-reaction-builder/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?><br>This class implements a builder for chemical reactions. |
| [BlendedSteering](-blended-steering/index.html) | [jvm]<br>open class [BlendedSteering](-blended-steering/index.html)<[T](-blended-steering/index.html)>(**environment**: [Euclidean2DEnvironment](../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](-blended-steering/index.html)>, **pedestrian**: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](-blended-steering/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-blended-steering/index.html)>) : [SteeringBehavior](-steering-behavior/index.html)<[T](-blended-steering/index.html)> <br>Steering behavior using [DistanceWeighted](../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-distance-weighted/index.html) steering strategy (= steering actions are summed with different weights depending on the distance to their target). |
| [BlendedSteeringWithPhysics](-blended-steering-with-physics/index.html) | [jvm]<br>class [BlendedSteeringWithPhysics](-blended-steering-with-physics/index.html)<[T](-blended-steering-with-physics/index.html)>(**environment**: [EuclideanPhysics2DEnvironmentWithGraph](../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](-blended-steering-with-physics/index.html), *, *>, **pedestrian**: [PhysicalPedestrian2D](../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](-blended-steering-with-physics/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-blended-steering-with-physics/index.html)>) : [BlendedSteering](-blended-steering/index.html)<[T](-blended-steering-with-physics/index.html)> <br>[BlendedSteering](-blended-steering/index.html) strategy for physical pedestrians, taking into account physical forces as well. |
| [ChemicalReaction](-chemical-reaction/index.html) | [jvm]<br>open class [ChemicalReaction](-chemical-reaction/index.html)<[T](-chemical-reaction/index.html)> : [AbstractReaction](-abstract-reaction/index.html)<[T](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> <br>concentration type |
| [CognitiveBehavior](-cognitive-behavior/index.html) | [jvm]<br>class [CognitiveBehavior](-cognitive-behavior/index.html)<[T](-cognitive-behavior/index.html), [V](-cognitive-behavior/index.html) : [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[V](-cognitive-behavior/index.html)>, [A](-cognitive-behavior/index.html) : [GeometricTransformation](../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[V](-cognitive-behavior/index.html)>>(**pedestrian**: [CognitivePedestrian](../it.unibo.alchemist.model.interfaces/-cognitive-pedestrian/index.html)<[T](-cognitive-behavior/index.html), [V](-cognitive-behavior/index.html), [A](-cognitive-behavior/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-cognitive-behavior/index.html)>) : [AbstractReaction](-abstract-reaction/index.html)<[T](-cognitive-behavior/index.html)> <br>Reaction representing the cognitive behavior of a pedestrian. |
| [Event](-event/index.html) | [jvm]<br>class [Event](-event/index.html)<[T](-event/index.html)> : [AbstractReaction](-abstract-reaction/index.html)<[T](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> <br>This reaction completely ignores the propensity conditioning of the conditions, and tries to run every time the [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html) wants to. |
| [NavigationPrioritisedSteering](-navigation-prioritised-steering/index.html) | [jvm]<br>open class [NavigationPrioritisedSteering](-navigation-prioritised-steering/index.html)<[T](-navigation-prioritised-steering/index.html), [N](-navigation-prioritised-steering/index.html) : [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**env**: [Euclidean2DEnvironmentWithGraph](../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment-with-graph/index.html)<*, [T](-navigation-prioritised-steering/index.html), [N](-navigation-prioritised-steering/index.html), *>, **pedestrian**: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](-navigation-prioritised-steering/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-navigation-prioritised-steering/index.html)>, **toleranceAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [SteeringBehavior](-steering-behavior/index.html)<[T](-navigation-prioritised-steering/index.html)> <br>A [SteeringBehavior](-steering-behavior/index.html) using [SinglePrevalent](../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-single-prevalent/index.html) steering strategy and accepting a collection of actions containing a single [NavigationAction2D](../it.unibo.alchemist.model.interfaces/index.html#-517309547%2FClasslikes%2F-134779887), which is used as the prevalent one. |
| [NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics/index.html) | [jvm]<br>class [NavigationPrioritisedSteeringWithPhysics](-navigation-prioritised-steering-with-physics/index.html)<[T](-navigation-prioritised-steering-with-physics/index.html), [N](-navigation-prioritised-steering-with-physics/index.html) : [ConvexPolygon](../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-convex-polygon/index.html)>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**env**: [EuclideanPhysics2DEnvironmentWithGraph](../it.unibo.alchemist.model.interfaces.environments/-euclidean-physics2-d-environment-with-graph/index.html)<*, [T](-navigation-prioritised-steering-with-physics/index.html), [N](-navigation-prioritised-steering-with-physics/index.html), *>, **pedestrian**: [PhysicalPedestrian2D](../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](-navigation-prioritised-steering-with-physics/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-navigation-prioritised-steering-with-physics/index.html)>, **toleranceAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **alpha**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [NavigationPrioritisedSteering](-navigation-prioritised-steering/index.html)<[T](-navigation-prioritised-steering-with-physics/index.html), [N](-navigation-prioritised-steering-with-physics/index.html)> <br>[NavigationPrioritisedSteering](-navigation-prioritised-steering/index.html) strategy for physical pedestrians, taking into account physical forces as well. |
| [PrioritySteering](-priority-steering/index.html) | [jvm]<br>class [PrioritySteering](-priority-steering/index.html)<[T](-priority-steering/index.html)>(**environment**: [Euclidean2DEnvironment](../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](-priority-steering/index.html)>, **pedestrian**: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](-priority-steering/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-priority-steering/index.html)>) : [SteeringBehavior](-steering-behavior/index.html)<[T](-priority-steering/index.html)> <br>Steering behavior using [Nearest](../it.unibo.alchemist.model.implementations.actions.steeringstrategies/-nearest/index.html) steering strategy (= the only action executed is the one with the nearest target). |
| [SAPEREGradient](-s-a-p-e-r-e-gradient/index.html) | [jvm]<br>class [SAPEREGradient](-s-a-p-e-r-e-gradient/index.html)<[P](-s-a-p-e-r-e-gradient/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)>?> : [AbstractReaction](-abstract-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> <br>This class provides a fast and stable gradient implementation, inspired on the NBR construct used in Proto. |
| [SAPEREReaction](-s-a-p-e-r-e-reaction/index.html) | [jvm]<br>class [SAPEREReaction](-s-a-p-e-r-e-reaction/index.html) : [AbstractReaction](-abstract-reaction/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>> <br>This class realizes a reaction with Lsa concentrations. |
| [SteeringBehavior](-steering-behavior/index.html) | [jvm]<br>open class [SteeringBehavior](-steering-behavior/index.html)<[T](-steering-behavior/index.html)>(**env**: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](-steering-behavior/index.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, **pedestrian**: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](-steering-behavior/index.html)>, **timeDistribution**: [TimeDistribution](../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](-steering-behavior/index.html)>, **steerStrategy**: [SteeringStrategy](../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](-steering-behavior/index.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [AbstractReaction](-abstract-reaction/index.html)<[T](-steering-behavior/index.html)> <br>Reaction representing the steering behavior of a pedestrian. |
