---
title: InitializedEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader](../index.html)/[InitializedEnvironment](index.html)



# InitializedEnvironment



[jvm]\
interface [InitializedEnvironment](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>

The result of the loading of an [environment](environment.html) with all the free variables instanced, also providing access to [dataExtractors](data-extractors.html).



## Properties


| Name | Summary |
|---|---|
| [dataExtractors](data-extractors.html) | [jvm]<br>abstract val [dataExtractors](data-extractors.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.html)><br>The data extractors for this environment. |
| [environment](environment.html) | [jvm]<br>abstract val [environment](environment.html): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)><br>The environment. |


## Inheritors


| Name |
|---|
| [EnvironmentAndExports](../-environment-and-exports/index.html) |

