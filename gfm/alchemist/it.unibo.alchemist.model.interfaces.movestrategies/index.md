//[alchemist](../../index.md)/[it.unibo.alchemist.model.interfaces.movestrategies](index.md)

# Package it.unibo.alchemist.model.interfaces.movestrategies

## Types

| Name | Summary |
|---|---|
| [RoutingStrategy](-routing-strategy/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [RoutingStrategy](-routing-strategy/index.md)<[P](-routing-strategy/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Strategy interface describing how the routing between two points happens. |
| [SpeedSelectionStrategy](-speed-selection-strategy/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [SpeedSelectionStrategy](-speed-selection-strategy/index.md)<[P](-speed-selection-strategy/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>Given the current target [Position](../it.unibo.alchemist.model.interfaces/-position/index.md), this strategy interface computes the current [it.unibo.alchemist.model.interfaces.Node](../it.unibo.alchemist.model.interfaces/-node/index.md)'s speed. |
| [TargetSelectionStrategy](-target-selection-strategy/index.md) | [jvm]<br>@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()<br>interface [TargetSelectionStrategy](-target-selection-strategy/index.md)<[P](-target-selection-strategy/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.model.implementations.layers/-step-layer/index.md)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>This interface models a strategy for selecting positions where to move. |
