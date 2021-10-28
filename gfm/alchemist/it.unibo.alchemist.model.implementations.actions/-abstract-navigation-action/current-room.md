//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[AbstractNavigationAction](index.md)/[currentRoom](current-room.md)

# currentRoom

[jvm]\
open override var [currentRoom](current-room.md): [N](index.md)? = null

The room (= environment's area) the [pedestrian](pedestrian.md) is into, this is cached and updated every time [update](update.md) is called so as to avoid potentially costly re-computations.
