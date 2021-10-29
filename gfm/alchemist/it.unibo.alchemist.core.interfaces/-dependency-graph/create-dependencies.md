//[alchemist](../../../index.md)/[it.unibo.alchemist.core.interfaces](../index.md)/[DependencyGraph](index.md)/[createDependencies](create-dependencies.md)

# createDependencies

[jvm]\
abstract fun [createDependencies](create-dependencies.md)(rh: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../../it.unibo.alchemist.model.interfaces/-node/index.md)>)

This method creates the dependencies when a new reaction is added to the environment. Please be careful when building the environment and populating the existing reactions map: this method assumes that all the dependencies among the existing reactions are correct and up to date.

## Parameters

jvm

| | |
|---|---|
| rh | the reaction handler whose dependencies should be calculated. |
