//[alchemist](../../../index.md)/[it.unibo.alchemist.loader](../index.md)/[Loader](index.md)/[getWith](get-with.md)

# getWith

[jvm]\
abstract fun <[T](get-with.md), [P](get-with.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> [getWith](get-with.md)(values: [Map](https://docs.oracle.com/javase/8/docs/api/java/util/Map.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [InitializedEnvironment](../-initialized-environment/index.md)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>

#### Return

an [InitializedEnvironment](../-initialized-environment/index.md) with all the variables set at the specified values. If the value is unspecified, the default is used instead

## Parameters

jvm

| | |
|---|---|
| values | a map specifying name-value bindings for the variables in this scenario |
| <T> | concentration type |
| <P> | position type |
