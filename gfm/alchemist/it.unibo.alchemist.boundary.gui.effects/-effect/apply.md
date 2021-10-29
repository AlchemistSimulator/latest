//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[Effect](index.md)/[apply](apply.md)

# apply

[jvm]\

@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()

~~open~~ ~~fun~~ [~~apply~~](apply.md)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~

Applies the effect.

#### Deprecated

use [apply](apply.md) instead.

## Parameters

jvm

| | |
|---|---|
| graphic | Graphics2D to use |
| node | the node to draw |
| x | x screen position |
| y | y screen position |

[jvm]\
open fun <[T](apply.md), [P](apply.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>?> [apply](apply.md)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-molecule-injector-g-u-i/index.md)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.monitors/-molecule-injector-g-u-i/index.md), [P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](../../it.unibo.alchemist.boundary.wormhole.implementation/-wormhole-swing/index.md)>)

Applies the effect.

## Parameters

jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | position type |
| g | graphics |
| n | node |
| env | environment |
| wormhole | the wormhole used to map environment's coords to screen coords |
