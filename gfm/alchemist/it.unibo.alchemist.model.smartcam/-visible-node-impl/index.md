//[alchemist](../../../index.md)/[it.unibo.alchemist.model.smartcam](../index.md)/[VisibleNodeImpl](index.md)

# VisibleNodeImpl

[jvm]\
class [VisibleNodeImpl](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, **position**: [P](index.md)) : [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.md)<[T](index.md), [P](index.md)> 

Basic implementation of [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.md).

## Constructors

| | |
|---|---|
| [VisibleNodeImpl](-visible-node-impl.md) | [jvm]<br>fun <[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>> [VisibleNodeImpl](-visible-node-impl.md)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, position: [P](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [node](node.md) | [jvm]<br>open override val [node](node.md): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)><br>The node seen. |
| [position](position.md) | [jvm]<br>open override val [position](position.md): [P](index.md)<br>The position of the node. |
