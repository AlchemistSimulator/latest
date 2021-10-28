//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[ChangeBiomolConcentrationInEnv](index.md)

# ChangeBiomolConcentrationInEnv

[jvm]\
class [ChangeBiomolConcentrationInEnv](index.md) : [AbstractRandomizableAction](../-abstract-randomizable-action/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> 

Action implementing the changing of the concentration of a given biomolecule in environment.

## Constructors

| | |
|---|---|
| [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md) | [jvm]<br>open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), deltaCon: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), randomGen: RandomGenerator)<br>Initialize a new [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md) that change concentration of the given [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md) of a "deltaCon" quantity. |
| [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md) | [jvm]<br>open fun [ChangeBiomolConcentrationInEnv](-change-biomol-concentration-in-env.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, biomolecule: [Biomolecule](../../it.unibo.alchemist.model.implementations.molecules/-biomolecule/index.md), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, randomGen: RandomGenerator)<br>Initialize a [ChangeBiomolConcentrationInEnv](index.md) with delta = -1. |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>): [Action](../../it.unibo.alchemist.model.interfaces/-action/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)> |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
