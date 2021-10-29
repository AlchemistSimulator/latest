---
title: drawFunction
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[FunctionDrawer](index.html)/[drawFunction](draw-function.html)



# drawFunction



[jvm]\
abstract fun <[T](draw-function.html), [P](draw-function.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>?> [drawFunction](draw-function.html)(function: (out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)) -> out [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html), environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](draw-function.html), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.html)>)



Draw the provided function.



## Parameters


jvm

| | |
|---|---|
| function | - the function |
| environment | - the environment (mainly used to make positions) |
| graphics | - the Graphics2D (where to draw the function) |
| wormhole | - the wormhole (to map env points to view points) |
| <T> | - concentration type |
| <P> | - position type |




