---
title: EnvironmentAndExports
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[EnvironmentAndExports](index.html)



# EnvironmentAndExports



[jvm]\
data class [EnvironmentAndExports](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, **dataExtractors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.html)>) : [InitializedEnvironment](../-initialized-environment/index.html)<[T](index.html), [P](index.html)> 

Pair-like implementation of [InitializedEnvironment](../-initialized-environment/index.html).



## Constructors


| | |
|---|---|
| [EnvironmentAndExports](-environment-and-exports.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [EnvironmentAndExports](-environment-and-exports.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>, dataExtractors: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.html)>) |


## Properties


| Name | Summary |
|---|---|
| [dataExtractors](data-extractors.html) | [jvm]<br>open override val [dataExtractors](data-extractors.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.html)><br>The data extractors for this environment. |
| [environment](environment.html) | [jvm]<br>open override val [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)><br>The environment. |

