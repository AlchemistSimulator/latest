//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.navigationstrategies](../index.md)/[DynamicPursuing](index.md)/[setDestination](set-destination.md)

# setDestination

[jvm]\
fun [setDestination](set-destination.md)(newDestination: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), voidVolatileMemory: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false)

Changes the destination of the strategy. If [voidVolatileMemory](set-destination.md) is true, the pedestrian's volatile memory is set to zero. This has two effects:

<ul><li>known impasses remain stored (hence the pedestrian will keep avoiding them)</li><li>rooms visited while pursuing the previous destination won't be penalised (= won't be avoided) Defaults to false.</li></ul>
