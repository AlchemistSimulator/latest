//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.movestrategies.target](index.md)

# Package it.unibo.alchemist.model.implementations.movestrategies.target

## Types

| Name | Summary |
|---|---|
| [FollowTarget](-follow-target/index.md) | [jvm]<br>open class [FollowTarget](-follow-target/index.md)<[T](-follow-target/index.md), [P](-follow-target/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.interfaces/-route/index.md)>?> : [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[P](../it.unibo.alchemist.model.interfaces/-route/index.md)> <br>This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate. |
| [FollowTargetOnMap](-follow-target-on-map/index.md) | [jvm]<br>open class [FollowTargetOnMap](-follow-target-on-map/index.md)<[T](-follow-target-on-map/index.md)> : [FollowTarget](-follow-target/index.md)<[T](../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md), [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> <br>This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate. |
| [FollowTrace](-follow-trace/index.md) | [jvm]<br>class [FollowTrace](-follow-trace/index.md) : [AbstractStrategyWithGPS](../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.md), [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.md)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> <br>This strategy follows a [Route](../it.unibo.alchemist.model.interfaces/-route/index.md). |
