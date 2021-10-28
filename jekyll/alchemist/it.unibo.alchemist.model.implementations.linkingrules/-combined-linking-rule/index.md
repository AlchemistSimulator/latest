---
title: CombinedLinkingRule
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[CombinedLinkingRule](index.html)



# CombinedLinkingRule



[jvm]\
class [CombinedLinkingRule](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**subRules**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)>>) : [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)> 

A meta-rule that combines multiple [subRules](sub-rules.html). If any mandates a link, such link is created (union of all links).



## Constructors


| | |
|---|---|
| [CombinedLinkingRule](-combined-linking-rule.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [CombinedLinkingRule](-combined-linking-rule.html)(subRules: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)>>) |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>): [SimpleNeighborhood](../../it.unibo.alchemist.model.implementations.neighborhoods/-simple-neighborhood/index.html)<[T](index.html), [P](index.html)> |
| [isLocallyConsistent](is-locally-consistent.html) | [jvm]<br>open override fun [isLocallyConsistent](is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [subRules](sub-rules.html) | [jvm]<br>val [subRules](sub-rules.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](index.html), [P](index.html)>> |

