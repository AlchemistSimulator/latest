//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.view](../index.md)/[SingleRunApp](index.md)/[addEffectGroups](add-effect-groups.md)

# addEffectGroups

[jvm]\
open fun [addEffectGroups](add-effect-groups.md)(effectGroups: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>>)

Adds the effects to the current effects.

## Parameters

jvm

| | |
|---|---|
| effectGroups | the group of effects to add |

#### Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) | if the application is already started |

[jvm]\
open fun [addEffectGroups](add-effect-groups.md)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))

Adds effect from a file.

## Parameters

jvm

| | |
|---|---|
| path | the path of the collection of EffectGroups. |

#### Throws

| | |
|---|---|
| [java.lang.IllegalStateException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalStateException.html) | if the application is already started |
