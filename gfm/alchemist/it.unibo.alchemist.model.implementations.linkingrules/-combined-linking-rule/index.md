//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[CombinedLinkingRule](index.md)

# CombinedLinkingRule

[jvm]\
class [CombinedLinkingRule](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**subRules**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)>>) : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)> 

A meta-rule that combines multiple [subRules](sub-rules.md). If any mandates a link, such link is created (union of all links).

## Constructors

| | |
|---|---|
| [CombinedLinkingRule](-combined-linking-rule.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [CombinedLinkingRule](-combined-linking-rule.md)(subRules: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)>>) |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>): [SimpleNeighborhood](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.md)<[T](index.md), [P](index.md)> |
| [isLocallyConsistent](is-locally-consistent.md) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [subRules](sub-rules.md) | [jvm]<br>val [subRules](sub-rules.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.md)<[T](index.md), [P](index.md)>> |
