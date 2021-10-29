---
title: ComponentViewPort
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation.adapter](../index.html)/[ComponentViewPort](index.html)



# ComponentViewPort



[jvm]\
open class [ComponentViewPort](index.html) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html)

Adapter class that adapts the AWT [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html) class to a generic ViewPort for usage in [it.unibo.alchemist.boundary.wormhole.implementation.AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.html).



## Constructors


| | |
|---|---|
| [ComponentViewPort](-component-view-port.html) | [jvm]<br>open fun [ComponentViewPort](-component-view-port.html)(component: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html))<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getHeight](get-height.html) | [jvm]<br>open fun [getHeight](get-height.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getWidth](get-width.html) | [jvm]<br>open fun [getWidth](get-width.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [component](component.html) | [jvm]<br>private open var [component](component.html): [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html) |

