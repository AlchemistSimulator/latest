//[alchemist](../../../index.md)/[it.unibo.alchemist.loader](../index.md)/[EnvironmentAndExports](index.md)

# EnvironmentAndExports

[jvm]\
data class [EnvironmentAndExports](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**environment**: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, **dataExtractors**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.md)>) : [InitializedEnvironment](../-initialized-environment/index.md)<[T](index.md), [P](index.md)> 

Pair-like implementation of [InitializedEnvironment](../-initialized-environment/index.md).

## Constructors

| | |
|---|---|
| [EnvironmentAndExports](-environment-and-exports.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [EnvironmentAndExports](-environment-and-exports.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>, dataExtractors: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.md)>) |

## Properties

| Name | Summary |
|---|---|
| [dataExtractors](data-extractors.md) | [jvm]<br>open override val [dataExtractors](data-extractors.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Extractor](../../it.unibo.alchemist.loader.export/-extractor/index.md)><br>The data extractors for this environment. |
| [environment](environment.md) | [jvm]<br>open override val [environment](environment.md): [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)><br>The environment. |
