//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[AbstractWormhole2D](index.md)/[AbstractWormhole2D](-abstract-wormhole2-d.md)

# AbstractWormhole2D

[jvm]\
open fun <[T](-abstract-wormhole2-d.md) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md)?> [AbstractWormhole2D](-abstract-wormhole2-d.md)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()view: [T](-abstract-wormhole2-d.md), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()viewTypeToPointAdapter: ([T](-abstract-wormhole2-d.md)) -> [PointAdapter](../-point-adapter/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)>)

Wormhole constructor for any [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md). Initializes a new instance directly setting the size of both view and environment, and the offset too.

## Parameters

jvm

| | |
|---|---|
| <T> | the type of the viewType |
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md) |
| view | the [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.md) of the UI used for implementing the wormhole. |
| viewTypeToPointAdapter | a [Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html) used to create the initial position of the wormhole. |
