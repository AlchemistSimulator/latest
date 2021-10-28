//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Dependency](index.md)/[makesDependent](makes-dependent.md)

# makesDependent

[jvm]\
open fun [makesDependent](makes-dependent.md)(dependency: [Dependency](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Determines whether the provided dependency depends on this dependency. The default behavior calls [dependsOn](depends-on.md), and provides a bidirectional dependency.

#### Return

true if this dependency generates a dependency with the provided one

## Parameters

jvm

| | |
|---|---|
| dependency | the dependency |
