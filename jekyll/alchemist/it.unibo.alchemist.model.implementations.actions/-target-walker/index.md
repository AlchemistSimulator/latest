---
title: TargetWalker
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[TargetWalker](index.html)



# TargetWalker



[jvm]\
open class [TargetWalker](index.html)<[T](index.html)> : [MoveOnMap](../-move-on-map/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |



## Constructors


| | |
|---|---|
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), @[Nullable](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nullable.html)()interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, trackMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), interactingMolecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>the environment |
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), interactingMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), interaction: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))<br>the environment |
| [TargetWalker](-target-walker.html) | [jvm]<br>open fun [TargetWalker](-target-walker.html)(environment: [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, trackMolecule: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>the environment |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](../-move-on-map/clone-action.html) | [jvm]<br>open fun [cloneAction](../-move-on-map/clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>): [MoveOnMap](../-move-on-map/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)><br>Fails, can't be cloned.<br>[jvm]<br>abstract fun [cloneAction](../../it.unibo.alchemist.model.interfaces/-action/clone-action.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>, p1: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)> |
| [execute](../-abstract-move-node/execute.html) | [jvm]<br>open fun [execute](../-abstract-move-node/execute.html)() |
| [getContext](../-abstract-move-node/get-context.html) | [jvm]<br>fun [getContext](../-abstract-move-node/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getEnvironment](../-move-on-map/get-environment.html) | [jvm]<br>fun [getEnvironment](../-move-on-map/get-environment.html)(): [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-routing-trace-dependant-speed/index.html)> |
| [getNextPosition](../-abstract-configurable-move-node/get-next-position.html) | [jvm]<br>fun [getNextPosition](../-abstract-configurable-move-node/get-next-position.html)(): [P](../../it.unibo.alchemist.model.interfaces/-timed-route/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](../-abstract-action/to-string.html) | [jvm]<br>open fun [toString](../-abstract-action/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [DEFAULT_INTERACTION](-d-e-f-a-u-l-t_-i-n-t-e-r-a-c-t-i-o-n.html) | [jvm]<br>val [DEFAULT_INTERACTION](-d-e-f-a-u-l-t_-i-n-t-e-r-a-c-t-i-o-n.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default interaction factor. |
| [DEFAULT_RANGE](-d-e-f-a-u-l-t_-r-a-n-g-e.html) | [jvm]<br>val [DEFAULT_RANGE](-d-e-f-a-u-l-t_-r-a-n-g-e.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default interaction range. |
| [DEFAULT_SPEED](-d-e-f-a-u-l-t_-s-p-e-e-d.html) | [jvm]<br>val [DEFAULT_SPEED](-d-e-f-a-u-l-t_-s-p-e-e-d.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Default speed in meters per second. |

