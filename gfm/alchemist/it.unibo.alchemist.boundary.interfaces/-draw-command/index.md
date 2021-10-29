//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interfaces](../index.md)/[DrawCommand](index.md)

# DrawCommand

[jvm]\
@[FunctionalInterface](https://docs.oracle.com/javase/8/docs/api/java/lang/FunctionalInterface.html)()

interface [DrawCommand](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>?> : [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<GraphicsContext, [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>> 

Functional interface that models a command for JavaFX thread to draw something on a javafx.scene.canvas.Canvas.

## Parameters

jvm

| | |
|---|---|
| <P> | The position type |

## Functions

| Name | Summary |
|---|---|
| [accept](accept.md) | [jvm]<br>abstract fun [accept](accept.md)(graphic: GraphicsContext, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)>)<br>The method consumes a graphic and a wormhole to draw something. |
| [andThen](index.md#1490799502%2FFunctions%2F-267951372) | [jvm]<br>open fun [andThen](index.md#1490799502%2FFunctions%2F-267951372)(after: [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [BiConsumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)<[T](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md), [U](https://docs.oracle.com/javase/8/docs/api/java/util/function/BiConsumer.html)> |
| [wrap](wrap.md) | [jvm]<br>open fun [wrap](wrap.md)(booleanSupplier: [Supplier](https://docs.oracle.com/javase/8/docs/api/java/util/function/Supplier.html)<[Boolean](https://docs.oracle.com/javase/8/docs/api/java/lang/Boolean.html)>): [DrawCommand](index.md)<[P](../../it.unibo.alchemist.boundary.monitor.generic/-numeric-label-monitor/index.md)><br>Wrapper method that wraps this [DrawCommand](index.md) into another that checks if should execute or not the [accept](accept.md) method. |
