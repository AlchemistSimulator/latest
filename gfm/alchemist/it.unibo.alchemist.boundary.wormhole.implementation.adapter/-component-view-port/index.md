//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation.adapter](../index.md)/[ComponentViewPort](index.md)

# ComponentViewPort

[jvm]\
open class [ComponentViewPort](index.md) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md)

Adapter class that adapts the AWT [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html) class to a generic ViewPort for usage in [it.unibo.alchemist.boundary.wormhole.implementation.AbstractWormhole2D](../../it.unibo.alchemist.boundary.wormhole.implementation/-abstract-wormhole2-d/index.md).

## Constructors

| | |
|---|---|
| [ComponentViewPort](-component-view-port.md) | [jvm]<br>open fun [ComponentViewPort](-component-view-port.md)(component: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html))<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getHeight](get-height.md) | [jvm]<br>open fun [getHeight](get-height.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getWidth](get-width.md) | [jvm]<br>open fun [getWidth](get-width.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Properties

| Name | Summary |
|---|---|
| [component](component.md) | [jvm]<br>private open var [component](component.md): [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html) |
