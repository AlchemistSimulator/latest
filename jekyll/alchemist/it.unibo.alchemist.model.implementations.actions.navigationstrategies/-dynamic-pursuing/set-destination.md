---
title: setDestination
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.html)/[DynamicPursuing](index.html)/[setDestination](set-destination.html)



# setDestination



[jvm]\
fun [setDestination](set-destination.html)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)



Changes the destination of the strategy. If [voidVolatileMemory](set-destination.html) is true, the pedestrian's volatile memory is set to zero. This has two effects:



<ul><li>known impasses remain stored (hence the pedestrian will keep avoiding them)</li><li>rooms visited while pursuing the previous destination won't be penalised (= won't be avoided) Defaults to false.</li></ul>




