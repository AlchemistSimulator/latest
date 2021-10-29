---
title: ProtectedExecutionEnvironment
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model](../../index.html)/[ProtelisIncarnation](../index.html)/[ProtectedExecutionEnvironment](index.html)



# ProtectedExecutionEnvironment



[jvm]\
class [ProtectedExecutionEnvironment](index.html) : ExecutionEnvironment

An ExecutionEnvironment that can read and shadow the content of a [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.html), but cannot modify it. This is used to prevent badly written properties to interact with the simulation flow.



## Constructors


| | |
|---|---|
| [ProtectedExecutionEnvironment](-protected-execution-environment.html) | [jvm]<br>open fun [ProtectedExecutionEnvironment](-protected-execution-environment.html)(node: [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.html) |


## Functions


| Name | Summary |
|---|---|
| [commit](commit.html) | [jvm]<br>open fun [commit](commit.html)() |
| [get](get.html) | [jvm]<br>open fun [get](get.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>open fun [get](get.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), defaultValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [has](has.html) | [jvm]<br>open fun [has](has.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [keySet](key-set.html) | [jvm]<br>open fun [keySet](key-set.html)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [put](put.html) | [jvm]<br>open fun [put](put.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [remove](remove.html) | [jvm]<br>open fun [remove](remove.html)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [setup](setup.html) | [jvm]<br>open fun [setup](setup.html)() |

