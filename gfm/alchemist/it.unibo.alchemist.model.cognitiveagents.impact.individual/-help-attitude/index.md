//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.md)/[HelpAttitude](index.md)

# HelpAttitude

[jvm]\
class [HelpAttitude](index.md)(**age**: [Age](../-age/index.md), **gender**: [Gender](../-gender/index.md)) : [Characteristic](../-characteristic/index.md)

The attitude of an agent towards helping another agent.

## Parameters

jvm

| | |
|---|---|
| age | the age of the helper. |
| gender | the gender of the helper. |

## Constructors

| | |
|---|---|
| [HelpAttitude](-help-attitude.md) | [jvm]<br>fun [HelpAttitude](-help-attitude.md)(age: [Age](../-age/index.md), gender: [Gender](../-gender/index.md))<br>    the age of the helper. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [level](level.md) | [jvm]<br>fun [level](level.md)(toHelpAge: [Age](../-age/index.md), toHelpGender: [Gender](../-gender/index.md), sameGroup: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The logic used to calculate the probability of helping. |
