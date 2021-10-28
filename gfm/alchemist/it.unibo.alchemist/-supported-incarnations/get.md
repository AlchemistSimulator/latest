//[alchemist](../../../index.md)/[it.unibo.alchemist](../index.md)/[SupportedIncarnations](index.md)/[get](get.md)

# get

[jvm]\
open fun <[T](get.md), [P](get.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>?> [get](get.md)(s: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[T](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md), [P](../../it.unibo.alchemist.model.implementations.movestrategies.speed/-constant-speed/index.md)>>

Fetches an incarnation whose name matches the supplied string.

#### Return

an [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html) containing the incarnation, if one with a matching name exists

## Parameters

jvm

| | |
|---|---|
| s | the name of the [Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.md) |
| <T> | [it.unibo.alchemist.model.interfaces.Concentration](../../it.unibo.alchemist.model.interfaces/-concentration/index.md) type |
| <P> | [it.unibo.alchemist.model.interfaces.Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type |
