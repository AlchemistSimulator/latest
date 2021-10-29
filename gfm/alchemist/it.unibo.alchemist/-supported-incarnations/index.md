//[alchemist](../../../index.md)/[it.unibo.alchemist](../index.md)/[SupportedIncarnations](index.md)

# SupportedIncarnations

[jvm]\
class [SupportedIncarnations](index.md)

This enum interfaces the generic components of the graphical interface with the specific incarnation details.

## Functions

| Name | Summary |
|---|---|
| [get](get.md) | [jvm]<br>open fun <[T](get.md), [P](get.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](get.md)>?> [get](get.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](get.md), [P](get.md)>><br>Fetches an incarnation whose name matches the supplied string. |
| [getAvailableIncarnations](get-available-incarnations.md) | [jvm]<br>open fun [getAvailableIncarnations](get-available-incarnations.md)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>The set of incarnations currently available. |
