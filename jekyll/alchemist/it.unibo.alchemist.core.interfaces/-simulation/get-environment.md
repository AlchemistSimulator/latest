---
title: getEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.core.interfaces](../index.html)/[Simulation](index.html)/[getEnvironment](get-environment.html)



# getEnvironment



[jvm]\
abstract fun [getEnvironment](get-environment.html)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>



Allows to access the current environment.



#### Return



a reference to the current Environment. The environment is not a copy but back-ends the real environment used in the simulation. Manipulate it carefully



