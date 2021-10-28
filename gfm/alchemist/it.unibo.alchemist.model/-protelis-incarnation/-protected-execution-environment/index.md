//[alchemist](../../../../index.md)/[it.unibo.alchemist.model](../../index.md)/[ProtelisIncarnation](../index.md)/[ProtectedExecutionEnvironment](index.md)

# ProtectedExecutionEnvironment

[jvm]\
class [ProtectedExecutionEnvironment](index.md) : ExecutionEnvironment

An ExecutionEnvironment that can read and shadow the content of a [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.md), but cannot modify it. This is used to prevent badly written properties to interact with the simulation flow.

## Constructors

| | |
|---|---|
| [ProtectedExecutionEnvironment](-protected-execution-environment.md) | [jvm]<br>open fun [ProtectedExecutionEnvironment](-protected-execution-environment.md)(node: [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.md) |

## Functions

| Name | Summary |
|---|---|
| [commit](commit.md) | [jvm]<br>open fun [commit](commit.md)() |
| [get](get.md) | [jvm]<br>open fun [get](get.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>open fun [get](get.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), defaultValue: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [has](has.md) | [jvm]<br>open fun [has](has.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [keySet](key-set.md) | [jvm]<br>open fun [keySet](key-set.md)(): [Set](https://docs.oracle.com/javase/8/docs/api/java/util/Set.html)<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)> |
| [put](put.md) | [jvm]<br>open fun [put](put.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), v: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [remove](remove.md) | [jvm]<br>open fun [remove](remove.md)(id: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [setup](setup.md) | [jvm]<br>open fun [setup](setup.md)() |
