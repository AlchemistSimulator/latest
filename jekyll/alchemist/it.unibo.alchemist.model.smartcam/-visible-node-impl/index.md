---
title: VisibleNodeImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.smartcam](../index.html)/[VisibleNodeImpl](index.html)



# VisibleNodeImpl



[jvm]\
class [VisibleNodeImpl](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**node**: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, **position**: [P](index.html)) : [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.html)<[T](index.html), [P](index.html)> 

Basic implementation of [VisibleNode](../../it.unibo.alchemist.model.interfaces/-visible-node/index.html).



## Constructors


| | |
|---|---|
| [VisibleNodeImpl](-visible-node-impl.html) | [jvm]<br>fun <[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>> [VisibleNodeImpl](-visible-node-impl.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, position: [P](index.html)) |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [node](node.html) | [jvm]<br>open override val [node](node.html): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)><br>The node seen. |
| [position](position.html) | [jvm]<br>open override val [position](position.html): [P](index.html)<br>The position of the node. |

