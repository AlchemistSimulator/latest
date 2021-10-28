//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[DependencyGraph](index.md)/[removeDependencies](remove-dependencies.md)

# removeDependencies

[jvm]\
abstract fun [removeDependencies](remove-dependencies.md)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)>)

This method removes all the dependencies (both in and out dependencies) for a given reaction handler. This method is meant to be used in order to keep the dependencies clean when removing a reaction.

## Parameters

jvm

| | |
|---|---|
| rh | the reaction handler whose dependencies will be deleted. |
