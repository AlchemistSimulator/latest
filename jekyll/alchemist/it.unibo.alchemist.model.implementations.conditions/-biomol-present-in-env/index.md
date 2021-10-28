---
title: BiomolPresentInEnv
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.conditions](../index.html)/[BiomolPresentInEnv](index.html)



# BiomolPresentInEnv



[jvm]\
class [BiomolPresentInEnv](index.html)<[P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [GenericMoleculePresent](../-generic-molecule-present/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>



## Parameters


jvm

| | |
|---|---|
| <P> | Position type |



## Constructors


| | |
|---|---|
| [BiomolPresentInEnv](-biomol-present-in-env.html) | [jvm]<br>open fun [BiomolPresentInEnv](-biomol-present-in-env.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.html), concentration: [Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html))<br>Initialize condition for extra-cellular environment, implemented as a set of [EnvironmentNode](../../it.unibo.alchemist.model.interfaces/-environment-node/index.html). |


## Functions


| Name | Summary |
|---|---|
| [cloneCondition](../-abstract-condition/clone-condition.html) | [jvm]<br>open fun [cloneCondition](../-abstract-condition/clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)>): [Condition](../../it.unibo.alchemist.model.interfaces/-condition/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)><br>open fun [cloneCondition](clone-condition.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, r: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [BiomolPresentInEnv](index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> |
| [getContext](get-context.html) | [jvm]<br>open fun [getContext](get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html)<br>abstract fun [getContext](../../it.unibo.alchemist.model.interfaces/-condition/get-context.html)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.html) |
| [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html) | [jvm]<br>fun [getInboundDependencies](../-abstract-condition/get-inbound-dependencies.html)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.html)> |
| [getMolecule](index.html#-310434243%2FFunctions%2F-134779887) | [jvm]<br>open fun [getMolecule](index.html#-310434243%2FFunctions%2F-134779887)(): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>Allows to access the molecule. |
| [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887) | [jvm]<br>open fun [getNode](../-lsa-standard-condition/index.html#-1460695024%2FFunctions%2F-134779887)(): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)> |
| [getPropensityContribution](get-propensity-contribution.html) | [jvm]<br>open fun [getPropensityContribution](get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Propensity influence is computed through the binomial coefficient.<br>[jvm]<br>abstract fun [getPropensityContribution](../../it.unibo.alchemist.model.interfaces/-condition/get-propensity-contribution.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getQuantity](../-generic-molecule-present/get-quantity.html) | [jvm]<br>open fun [getQuantity](../-generic-molecule-present/get-quantity.html)(): [T](../../it.unibo.alchemist.model.implementations.reactions/-chemical-reaction/index.html)<br>Allows to access the threshold. |
| [isValid](is-valid.html) | [jvm]<br>open fun [isValid](is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the concentration of the molecule is higher or equal the value.<br>[jvm]<br>abstract fun [isValid](../../it.unibo.alchemist.model.interfaces/-condition/is-valid.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html) | [jvm]<br>open fun [reactionReady](../../it.unibo.alchemist.model.interfaces/-condition/reaction-ready.html)() |
| [toString](../-abstract-condition/to-string.html) | [jvm]<br>open fun [toString](../-abstract-condition/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>open fun [toString](../-generic-molecule-present/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
