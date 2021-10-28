//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[Simulation](index.md)/[getEnvironment](get-environment.md)

# getEnvironment

[jvm]\
abstract fun [getEnvironment](get-environment.md)(): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-action/index.md), [P](index.md)>

Allows to access the current environment.

#### Return

a reference to the current Environment. The environment is not a copy but back-ends the real environment used in the simulation. Manipulate it carefully
