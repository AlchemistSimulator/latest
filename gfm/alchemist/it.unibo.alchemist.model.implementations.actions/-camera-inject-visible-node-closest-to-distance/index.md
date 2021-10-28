//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[CameraInjectVisibleNodeClosestToDistance](index.md)

# CameraInjectVisibleNodeClosestToDistance

[jvm]\
class [CameraInjectVisibleNodeClosestToDistance](index.md)(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **visionMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), **targetMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) : [AbstractAction](../-abstract-action/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> 

Given a list of [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.md) associated to visionMolecule, it finds the closest to a point located at distance from node in the direction of node's heading, and injects its position in targetMolecule.

If there are no [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.md)s, targetMolecule will be removed from node.

## Constructors

| | |
|---|---|
| [CameraInjectVisibleNodeClosestToDistance](-camera-inject-visible-node-closest-to-distance.md) | [jvm]<br>fun [CameraInjectVisibleNodeClosestToDistance](-camera-inject-visible-node-closest-to-distance.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), visionMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open override fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [CameraInjectVisibleNodeClosestToDistance](index.md) |
| [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.md#1970369254%2FFunctions%2F-267951372)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)) |
| [execute](execute.md) | [jvm]<br>open override fun [execute](execute.md)() |
| [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372) | [jvm]<br>fun [getConcentration](../-camera-see/index.md#-1328510210%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getContext](get-context.md) | [jvm]<br>open override fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372) | [jvm]<br>open fun [getNode](../-camera-see/index.md#-1981508984%2FFunctions%2F-267951372)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372) | [jvm]<br>fun [nodeContains](../-camera-see/index.md#1662898740%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372) | [jvm]<br>fun [removeConcentration](../-camera-see/index.md#-151459758%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) |
| [setConcentration](../-camera-see/index.md#-637110410%2FFunctions%2F-267951372) | [jvm]<br>fun [setConcentration](../-camera-see/index.md#-637110410%2FFunctions%2F-267951372)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md), p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [toString](../-abstract-action/to-string.md) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
