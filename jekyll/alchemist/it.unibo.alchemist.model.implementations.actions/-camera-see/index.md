---
title: CameraSee
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CameraSee](index.html)



# CameraSee



[jvm]\
class [CameraSee](index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **angle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **outputMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), **filterByMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)?) : [AbstractAction](../-abstract-action/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> 

Checks nodes in the environment and writes in outputMolecule the list of [it.unibo.alchemist.model.interfaces.VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.html), containing filterByMolecule. [distance](distance.html) and [angle](angle.html) define the field of view.



## Constructors


| | |
|---|---|
| [CameraSee](-camera-see.html) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [CameraSee](-camera-see.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), outputMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html) = SimpleMolecule("vision"), filterByMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)? = null) |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open override fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [CameraSee](index.html) |
| [declareDependencyTo](index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](execute.html) | [jvm]<br>open override fun [execute](execute.html)() |
| [getConcentration](index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getContext](get-context.html) | [jvm]<br>open override fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](index.html#-1981508984%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](index.html#-1981508984%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [nodeContains](index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](index.html#-637110410%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](index.html#-637110410%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [angle](angle.html) | [jvm]<br>val [angle](angle.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Angle in degrees of the field of view. |
| [distance](distance.html) | [jvm]<br>val [distance](distance.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance of the field of view. |

