//[alchemist](../../../index.md)/[it.unibo.alchemist.grid.simulation](../index.md)/[RemoteResultImpl](index.md)

# RemoteResultImpl

[jvm]\
class [RemoteResultImpl](index.md) : [RemoteResult](../-remote-result/index.md)

[RemoteResult](../-remote-result/index.md) implementation.

## Constructors

| | |
|---|---|
| [RemoteResultImpl](-remote-result-impl.md) | [jvm]<br>open fun [RemoteResultImpl](-remote-result-impl.md)(result: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), workerNode: [UUID](https://docs.oracle.com/javase/8/docs/api/java/util/UUID.html), simulationErrors: [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Throwable](https://docs.oracle.com/javase/8/docs/api/java/lang/Throwable.html)>, config: [SimulationConfig](../../it.unibo.alchemist.grid.config/-simulation-config/index.md))<br>Result file's content as string |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [saveLocally](save-locally.md) | [jvm]<br>open fun [saveLocally](save-locally.md)(targetFile: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Save simulation's result in a local file. |
