---
title: makesDependent
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[Dependency](index.html)/[makesDependent](makes-dependent.html)



# makesDependent



[jvm]\
open fun [makesDependent](makes-dependent.html)(dependency: [Dependency](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Determines whether the provided dependency depends on this dependency. The default behavior calls [dependsOn](depends-on.html), and provides a bidirectional dependency.



#### Return



true if this dependency generates a dependency with the provided one



## Parameters


jvm

| | |
|---|---|
| dependency | the dependency |




