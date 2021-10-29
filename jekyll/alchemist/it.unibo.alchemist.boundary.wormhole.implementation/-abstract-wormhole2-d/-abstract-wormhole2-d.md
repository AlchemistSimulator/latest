---
title: AbstractWormhole2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[AbstractWormhole2D](index.html)/[AbstractWormhole2D](-abstract-wormhole2-d.html)



# AbstractWormhole2D



[jvm]\
open fun <[T](-abstract-wormhole2-d.html) : [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html)?> [AbstractWormhole2D](-abstract-wormhole2-d.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>, @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()view: [T](-abstract-wormhole2-d.html), @[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()viewTypeToPointAdapter: ([T](-abstract-wormhole2-d.html)) -> [PointAdapter](../-point-adapter/index.html)<[P](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)>)



Wormhole constructor for any [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html). Initializes a new instance directly setting the size of both view and environment, and the offset too.



## Parameters


jvm

| | |
|---|---|
| <T> | the type of the viewType |
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |
| view | the [ViewPort](../../it.unibo.alchemist.boundary.wormhole.interfaces/-view-port/index.html) of the UI used for implementing the wormhole. |
| viewTypeToPointAdapter | a [Function](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html) used to create the initial position of the wormhole. |




