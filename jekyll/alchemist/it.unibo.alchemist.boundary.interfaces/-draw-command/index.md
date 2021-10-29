---
title: DrawCommand
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interfaces](../index.html)/[DrawCommand](index.html)



# DrawCommand



[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()



interface [DrawCommand](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> : [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<GraphicsContext, [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>> 

Functional interface that models a command for JavaFX thread to draw something on a javafx.scene.canvas.Canvas.



## Parameters


jvm

| | |
|---|---|
| <P> | The position type |



## Functions


| Name | Summary |
|---|---|
| [accept](accept.html) | [jvm]<br>abstract fun [accept](accept.html)(graphic: GraphicsContext, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>)<br>The method consumes a graphic and a wormhole to draw something. |
| [andThen](index.html#1490799502%2FFunctions%2F-134779887) | [jvm]<br>open fun [andThen](index.html#1490799502%2FFunctions%2F-134779887)(after: [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<T, [U](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)> |
| [wrap](wrap.html) | [jvm]<br>open fun [wrap](wrap.html)(booleanSupplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): [DrawCommand](index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)><br>Wrapper method that wraps this [DrawCommand](index.html) into another that checks if should execute or not the [accept](accept.html) method. |

