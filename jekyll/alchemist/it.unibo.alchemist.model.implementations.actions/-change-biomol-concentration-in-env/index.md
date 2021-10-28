---
title: ChangeBiomolConcentrationInEnv
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ChangeBiomolConcentrationInEnv](index.html)



# ChangeBiomolConcentrationInEnv



[jvm]\
class [ChangeBiomolConcentrationInEnv](index.html) : [AbstractRandomizableAction](../-abstract-randomizable-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

Action implementing the changing of the concentration of a given biomolecule in environment.



## Constructors


| | |
|---|---|
| [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html) | [jvm]<br>open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), deltaCon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGen: RandomGenerator)<br>Initialize a new [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) that change concentration of the given [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html) of a "deltaCon" quantity. |
| [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html) | [jvm]<br>open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGen: RandomGenerator)<br>Initialize a [ChangeBiomolConcentrationInEnv](index.html) with delta = -1. |


## Functions


| Name | Summary |
|---|---|
| [cloneAction](clone-action.html) | [jvm]<br>open fun [cloneAction](clone-action.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [execute](execute.html) | [jvm]<br>open fun [execute](execute.html)() |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

