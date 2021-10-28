//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CameraSee](index.md)

# CameraSee

[jvm]\
class [CameraSee](index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()constructor(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **angle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **outputMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), **filterByMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)?) : [AbstractAction](../-abstract-action/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> 

Checks nodes in the environment and writes in outputMolecule the list of [it.unibo.alchemist.model.interfaces.VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.md), containing filterByMolecule. [distance](distance.md) and [angle](angle.md) define the field of view.

## Constructors

| | |
|---|---|
| [CameraSee](-camera-see.md) | [jvm]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()<br>fun [CameraSee](-camera-see.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), outputMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md) = SimpleMolecule("vision"), filterByMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)? = null) |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open override fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [CameraSee](index.md) |
| [declareDependencyTo](index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](execute.md) | [jvm]<br>open override fun [execute](execute.md)() |
| [getConcentration](index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getContext](get-context.md) | [jvm]<br>open override fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](index.md#-1981508984%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](index.md#-1981508984%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [nodeContains](index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](index.md#-637110410%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](index.md#-637110410%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [angle](angle.md) | [jvm]<br>val [angle](angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Angle in degrees of the field of view. |
| [distance](distance.md) | [jvm]<br>val [distance](distance.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Distance of the field of view. |
