//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Environment](index.md)/[getLayer](get-layer.md)

# getLayer

[jvm]\
abstract fun [getLayer](get-layer.md)(m: [Molecule](../-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.md)<[T](../-action/index.md), [P](../../it.unibo.alchemist.core.interfaces/-simulation/index.md)>>

Get the layer associate to the given molecule. If no Layer is associated with the given molecule, return an empty optional.

#### Return

the [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the [Layer](../-layer/index.md) associated with the requested molecule

## Parameters

jvm

| | |
|---|---|
| m | the [Molecule](../-molecule/index.md) |