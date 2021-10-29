---
title: it.unibo.alchemist.model.implementations.movestrategies.target
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.target](index.html)



# Package it.unibo.alchemist.model.implementations.movestrategies.target



## Types


| Name | Summary |
|---|---|
| [FollowTarget](-follow-target/index.html) | [jvm]<br>open class [FollowTarget](-follow-target/index.html)<[T](-follow-target/index.html), [P](-follow-target/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist/-supported-incarnations/get.html)>?> : [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[P](../it.unibo.alchemist/-supported-incarnations/get.html)> <br>This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate. |
| [FollowTargetOnMap](-follow-target-on-map/index.html) | [jvm]<br>open class [FollowTargetOnMap](-follow-target-on-map/index.html)<[T](-follow-target-on-map/index.html)> : [FollowTarget](-follow-target/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>This strategy reads the value of a "target" molecule and tries to interpret it as a coordinate. |
| [FollowTrace](-follow-trace/index.html) | [jvm]<br>class [FollowTrace](-follow-trace/index.html) : [AbstractStrategyWithGPS](../it.unibo.alchemist.model.implementations.movestrategies/-abstract-strategy-with-g-p-s/index.html), [TargetSelectionStrategy](../it.unibo.alchemist.model.interfaces.movestrategies/-target-selection-strategy/index.html)<[GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> <br>This strategy follows a [Route](../it.unibo.alchemist.model.interfaces/-route/index.html). |

