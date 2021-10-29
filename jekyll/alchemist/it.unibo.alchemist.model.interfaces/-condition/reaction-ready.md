---
title: reactionReady
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Condition](index.html)/[reactionReady](reaction-ready.html)



# reactionReady



[jvm]\
open fun [reactionReady](reaction-ready.html)()



This method is called by the [it.unibo.alchemist.core.interfaces.Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html) once the [Reaction](../-reaction/index.html) whose this [Condition](index.html) belongs to is the next one to be executed, and all its conditions passed (namely, the next operation will be the reaction execution). It can be used to perform sanity checks, as well as for registering the status of the simulated world for future comparisons. Defaults to an empty implementation.




