---
title: addEffectGroups
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view](../index.html)/[SingleRunApp](index.html)/[addEffectGroups](add-effect-groups.html)



# addEffectGroups



[jvm]\
open fun [addEffectGroups](add-effect-groups.html)(effectGroups: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[EffectGroup](../../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>>)



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
open fun [addEffectGroups](add-effect-groups.html)(path: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))



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



