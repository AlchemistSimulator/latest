//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[Reaction](index.md)/[getConditions](get-conditions.md)

# getConditions

[jvm]\
abstract fun [getConditions](get-conditions.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Condition](../-condition/index.md)<[T](../-node/index.md)>>

#### Return

The list of [Condition](../-condition/index.md)s of the [Reaction](index.md). There is no specification if the list will be a copy of the internal list or a reference. It will depend on implementations. Please be careful when you modify this list.
