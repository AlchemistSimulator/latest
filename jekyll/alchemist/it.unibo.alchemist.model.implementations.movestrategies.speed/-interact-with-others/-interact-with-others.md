---
title: InteractWithOthers
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.movestrategies.speed](../index.html)/[InteractWithOthers](index.html)/[InteractWithOthers](-interact-with-others.html)



# InteractWithOthers



[jvm]\
open fun [InteractWithOthers](-interact-with-others.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html), [P](../../it.unibo.alchemist/-supported-incarnations/get.html)>, n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist/-supported-incarnations/get.html)>, inter: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment |
| n | the node |
| reaction | the reaction |
| inter | the molecule that identifies an interacting node |
| speed | the normal speed of the node |
| radius | the radius where to search for interacting nodes |
| interaction | the interaction factor. This will be multiplied by a crowd factor dynamically computed, and the speed will be divided by the number obtained |




