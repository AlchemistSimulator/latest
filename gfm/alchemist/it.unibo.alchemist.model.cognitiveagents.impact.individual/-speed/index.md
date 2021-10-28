//[alchemist](../../../index.md)/[it.unibo.alchemist.model.cognitiveagents.impact.individual](../index.md)/[Speed](index.md)

# Speed

[jvm]\
class [Speed](index.md)(**age**: [Age](../-age/index.md), **gender**: [Gender](../-gender/index.md), **rg**: RandomGenerator) : [Characteristic](../-characteristic/index.md)

The speed of an agent considering its age, gender and a random factor.

## Parameters

jvm

| | |
|---|---|
| age | the age of the agent. |
| gender | the gender of the agent. |
| rg | the simulation {@link RandomGenerator}. |

## Constructors

| | |
|---|---|
| [Speed](-speed.md) | [jvm]<br>fun [Speed](-speed.md)(age: [Age](../-age/index.md), gender: [Gender](../-gender/index.md), rg: RandomGenerator)<br>    the age of the agent. |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [running](running.md) | [jvm]<br>val [running](running.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The running speed of the agent. |
| [walking](walking.md) | [jvm]<br>val [walking](walking.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The walking speed of the agent. |
