//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Condition](index.md)/[reactionReady](reaction-ready.md)

# reactionReady

[jvm]\
open fun [reactionReady](reaction-ready.md)()

This method is called by the [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.md) once the [Reaction](../-reaction/index.md) whose this [Condition](index.md) belongs to is the next one to be executed, and all its conditions passed (namely, the next operation will be the reaction execution). It can be used to perform sanity checks, as well as for registering the status of the simulated world for future comparisons. Defaults to an empty implementation.
