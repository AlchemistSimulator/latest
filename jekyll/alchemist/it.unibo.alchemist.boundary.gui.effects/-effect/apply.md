---
title: apply
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[Effect](index.html)/[apply](apply.html)



# apply



[jvm]\




@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~open~~ ~~fun~~ [~~apply~~](apply.html)~~(~~~~graphic~~~~:~~ [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html)~~,~~ ~~node~~~~:~~ [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>~~,~~ ~~x~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~,~~ ~~y~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~



Applies the effect.



#### Deprecated



use [apply](apply.html) instead.



## Parameters


jvm

| | |
|---|---|
| graphic | Graphics2D to use |
| node | the node to draw |
| x | x screen position |
| y | y screen position |





[jvm]\
open fun <[T](apply.html), [P](apply.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>?> [apply](apply.html)(g: [Graphics2D](https://docs.oracle.com/javase/8/docs/api/java/awt/Graphics2D.html), n: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-graphical2-d-output-monitor/index.html)>)



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




