---
title: HelpAttitude
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.html)/[HelpAttitude](index.html)



# HelpAttitude



[jvm]\
class [HelpAttitude](index.html)(**age**: [Age](../-age/index.html), **gender**: [Gender](../-gender/index.html)) : [Characteristic](../-characteristic/index.html)

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
| [HelpAttitude](-help-attitude.html) | [jvm]<br>fun [HelpAttitude](-help-attitude.html)(age: [Age](../-age/index.html), gender: [Gender](../-gender/index.html))<br>    the age of the helper. |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [level](level.html) | [jvm]<br>fun [level](level.html)(toHelpAge: [Age](../-age/index.html), toHelpGender: [Gender](../-gender/index.html), sameGroup: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The logic used to calculate the probability of helping. |

