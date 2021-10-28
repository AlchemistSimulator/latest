---
title: get
---
//[alchemist](../../../index.html)/[it.unibo.alchemist](../index.html)/[SupportedIncarnations](index.html)/[get](get.html)



# get



[jvm]\
open fun <[T](get.html), [P](get.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>?> [get](get.html)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-step-layer/index.html)>>



Fetches an incarnation whose name matches the supplied string.



#### Return



an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the incarnation, if one with a matching name exists



## Parameters


jvm

| | |
|---|---|
| s | the name of the [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html) |
| <T> | [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.html) type |
| <P> | [it.unibo.alchemist.model.interfaces.Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |




