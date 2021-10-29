---
title: ContainsMolecule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[ContainsMolecule](index.html)



# ContainsMolecule



[jvm]\
class [ContainsMolecule](index.html)<[T](index.html)>(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **molecule**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) : [AbstractCondition](../-abstract-condition/index.html)<[T](index.html)> 

The condition is valid if the node contains the molecule.



## Constructors


| | |
|---|---|
| [ContainsMolecule](-contains-molecule.html) | [jvm]<br>fun <[T](index.html)> [ContainsMolecule](-contains-molecule.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, molecule: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](index.html#1114898962%2FFunctions%2F-134779887) | [jvm]<br>open override fun [cloneCondition](index.html#1114898962%2FFunctions%2F-134779887)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](index.html)> |
| [declareDependencyOn](../-no-other-reaction-can-execute/index.html#-94060918%2FFunctions%2F-134779887) | [jvm]<br>fun [declareDependencyOn](../-no-other-reaction-can-execute/index.html#-94060918%2FFunctions%2F-134779887)(m: [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)) |
| [getContext](get-context.html) | [jvm]<br>open override fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>override fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open override fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open override fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isValid](is-valid.html) | [jvm]<br>open override fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](../-abstract-condition/to-string.html) | [jvm]<br>open override fun [toString](../-abstract-condition/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

