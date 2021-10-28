//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[DrawLayers](index.md)/[drawLayers](draw-layers.md)

# drawLayers

[jvm]\
abstract fun <[T](draw-layers.md), [P](draw-layers.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>?> [drawLayers](draw-layers.md)(toDraw: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>, graphics: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.md)>)

Effectively draw the layers.

## Parameters

jvm

| | |
|---|---|
| toDraw | - the layers to draw |
| environment | - the environment (mainly used to create positions) |
| graphics | - the graphics2D |
| wormhole | - the wormhole |
| <T> | - node concentration type |
| <P> | - position type |