---
title: getLayer
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Environment](index.html)/[getLayer](get-layer.html)



# getLayer



[jvm]\
abstract fun [getLayer](get-layer.html)(m: [Molecule](../-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../-layer/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)>>



Get the layer associate to the given molecule. If no Layer is associated with the given molecule, return an empty optional.



#### Return



the [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the [Layer](../-layer/index.html) associated with the requested molecule



## Parameters


jvm

| | |
|---|---|
| m | the [Molecule](../-molecule/index.html) |




