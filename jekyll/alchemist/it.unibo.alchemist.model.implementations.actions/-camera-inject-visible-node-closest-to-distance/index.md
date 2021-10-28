---
title: CameraInjectVisibleNodeClosestToDistance
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CameraInjectVisibleNodeClosestToDistance](index.html)



# CameraInjectVisibleNodeClosestToDistance



[jvm]\
class [CameraInjectVisibleNodeClosestToDistance](index.html)(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **env**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, **distance**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **visionMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), **targetMolecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) : [AbstractAction](../-abstract-action/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> 

Given a list of [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.html) associated to visionMolecule, it finds the closest to a point located at distance from node in the direction of node's heading, and injects its position in targetMolecule.



If there are no [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.html)s, targetMolecule will be removed from node.



## Constructors


| | |
|---|---|
| [CameraInjectVisibleNodeClosestToDistance](-camera-inject-visible-node-closest-to-distance.html) | [jvm]<br>fun [CameraInjectVisibleNodeClosestToDistance](-camera-inject-visible-node-closest-to-distance.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, env: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), visionMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), targetMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open override fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [CameraInjectVisibleNodeClosestToDistance](index.html) |
| [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyTo](../-camera-see/index.html#1970369254%2FFunctions%2F-134779887)(p0: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [execute](execute.html) | [jvm]<br>open override fun [execute](execute.html)() |
| [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887) | [jvm]<br>fun [getConcentration](../-camera-see/index.html#-1328510210%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getContext](get-context.html) | [jvm]<br>open override fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getNode](../-camera-see/index.html#-1981508984%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-camera-see/index.html#-1981508984%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>override fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887) | [jvm]<br>fun [nodeContains](../-camera-see/index.html#1662898740%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887) | [jvm]<br>fun [removeConcentration](../-camera-see/index.html#-151459758%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |
| [setConcentration](../-camera-see/index.html#-637110410%2FFunctions%2F-134779887) | [jvm]<br>fun [setConcentration](../-camera-see/index.html#-637110410%2FFunctions%2F-134779887)(p0: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), p1: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-action/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

