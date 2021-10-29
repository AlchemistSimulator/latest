---
title: InteractWithOthers
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[InteractWithOthers](index.html)



# InteractWithOthers



[jvm]\
class [InteractWithOthers](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> : [SpeedSelectionStrategy](../../it.unibo.alchemist.model.interfaces.movestrategies/-speed-selection-strategy/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)> 

This strategy slows down nodes depending on how many "interacting" nodes are found in the surroundings. It is an attempt at modeling crowding slow-downs.



## Parameters


jvm

| | |
|---|---|
| <P> | position type |
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [InteractWithOthers](-interact-with-others.html) | [jvm]<br>open fun [InteractWithOthers](-interact-with-others.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>, inter: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [getNodeMovementLength](get-node-movement-length.html) | [jvm]<br>open fun [getNodeMovementLength](get-node-movement-length.html)(target: [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) describing where the [it.unibo.alchemist.model.interfaces.Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) is directed |

