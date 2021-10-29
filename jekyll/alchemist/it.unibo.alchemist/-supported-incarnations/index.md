---
title: SupportedIncarnations
---
//[alchemist](../../../index.html)/[it.unibo.alchemist](../index.html)/[SupportedIncarnations](index.html)



# SupportedIncarnations



[jvm]\
class [SupportedIncarnations](index.html)

This enum interfaces the generic components of the graphical interface with the specific incarnation details.



## Functions


| Name | Summary |
|---|---|
| [get](get.html) | [jvm]<br>open fun <[T](get.html), [P](get.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>?> [get](get.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.interfaces/-route/index.html)>><br>Fetches an incarnation whose name matches the supplied string. |
| [getAvailableIncarnations](get-available-incarnations.html) | [jvm]<br>open fun [getAvailableIncarnations](get-available-incarnations.html)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>The set of incarnations currently available. |

