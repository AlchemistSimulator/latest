//[alchemist](../../../index.md)/[it.unibo.alchemist.loader](../index.md)/[InitializedEnvironment](index.md)

# InitializedEnvironment

[jvm]\
interface [InitializedEnvironment](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>

The result of the loading of an [environment](environment.md) with all the free variables instanced, also providing access to [dataExtractors](data-extractors.md).

## Properties

| Name | Summary |
|---|---|
| [dataExtractors](data-extractors.md) | [jvm]<br>abstract val [dataExtractors](data-extractors.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.md)><br>The data extractors for this environment. |
| [environment](environment.md) | [jvm]<br>abstract val [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)><br>The environment. |

## Inheritors

| Name |
|---|
| [EnvironmentAndExports](../-environment-and-exports/index.md) |
