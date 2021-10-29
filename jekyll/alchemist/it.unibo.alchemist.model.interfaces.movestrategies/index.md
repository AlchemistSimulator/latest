---
title: it.unibo.alchemist.model.interfaces.movestrategies
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.interfaces.movestrategies](index.html)



# Package it.unibo.alchemist.model.interfaces.movestrategies



## Types


| Name | Summary |
|---|---|
| [RoutingStrategy](-routing-strategy/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [RoutingStrategy](-routing-strategy/index.html)<[P](-routing-strategy/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Strategy interface describing how the routing between two points happens. |
| [SpeedSelectionStrategy](-speed-selection-strategy/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [SpeedSelectionStrategy](-speed-selection-strategy/index.html)<[P](-speed-selection-strategy/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Given the current target [Position](../it.unibo.alchemist.model.interfaces/-position/index.html), this strategy interface computes the current [it.unibo.alchemist.model.interfaces.Node](../it.unibo.alchemist.model.interfaces/-node/index.html)'s speed. |
| [TargetSelectionStrategy](-target-selection-strategy/index.html) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [TargetSelectionStrategy](-target-selection-strategy/index.html)<[P](-target-selection-strategy/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>This interface models a strategy for selecting positions where to move. |

