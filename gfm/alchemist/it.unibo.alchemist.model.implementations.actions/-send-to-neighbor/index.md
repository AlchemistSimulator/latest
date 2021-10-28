//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions](../index.md)/[SendToNeighbor](index.md)

# SendToNeighbor

[jvm]\
class [SendToNeighbor](index.md) : [AbstractAction](../-abstract-action/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>

## Constructors

| | |
|---|---|
| [SendToNeighbor](-send-to-neighbor.md) | [jvm]<br>open fun [SendToNeighbor](-send-to-neighbor.md)(node: [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, program: [RunProtelisProgram](../-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>)<br>the local node |

## Functions

| Name | Summary |
|---|---|
| [cloneAction](clone-action.md) | [jvm]<br>open fun [cloneAction](clone-action.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [SendToNeighbor](index.md) |
| [execute](execute.md) | [jvm]<br>open fun [execute](execute.md)() |
| [getContext](get-context.md) | [jvm]<br>open fun [getContext](get-context.md)(): [Context](../../it.unibo.alchemist.model.interfaces/-context/index.md) |
| [getNode](get-node.md) | [jvm]<br>open fun [getNode](get-node.md)(): [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> |
| [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md) | [jvm]<br>fun [getOutboundDependencies](../-abstract-action/get-outbound-dependencies.md)(): ListSet<out [Dependency](../../it.unibo.alchemist.model.interfaces/-dependency/index.md)> |
| [getProtelisProgram](get-protelis-program.md) | [jvm]<br>open fun [getProtelisProgram](get-protelis-program.md)(): [RunProtelisProgram](../-run-protelis-program/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>the [RunProtelisProgram](../-run-protelis-program/index.md) whose data will be sent |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
