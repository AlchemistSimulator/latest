---
title: RemoteResultImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.grid.simulation](../index.html)/[RemoteResultImpl](index.html)



# RemoteResultImpl



[jvm]\
class [RemoteResultImpl](index.html) : [RemoteResult](../-remote-result/index.html)

[RemoteResult](../-remote-result/index.html) implementation.



## Constructors


| | |
|---|---|
| [RemoteResultImpl](-remote-result-impl.html) | [jvm]<br>open fun [RemoteResultImpl](-remote-result-impl.html)(result: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), workerNode: [UUID](https://docs.oracle.com/javase/8/docs/api/java/util/UUID.html), simulationErrors: [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)>, config: [SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.html))<br>Result file's content as string |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [saveLocally](save-locally.html) | [jvm]<br>open fun [saveLocally](save-locally.html)(targetFile: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Save simulation's result in a local file. |

