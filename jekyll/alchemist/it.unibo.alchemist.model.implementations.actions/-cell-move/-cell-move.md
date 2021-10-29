---
title: CellMove
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[CellMove](index.html)/[CellMove](-cell-move.html)



# CellMove



[jvm]\
open fun [CellMove](-cell-move.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../../it.unibo.alchemist.model/-biochemistry-incarnation/index.html)>, node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html)>, inPercent: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), delta: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



Initialize an Action that move the cell of a given space delta, which can be expressed in percent of the cell's diameter or in absolute. If the cell has diameter 0, the only way to express delta is absolute. There's no way to decide the direction of the cell by this [it.unibo.alchemist.model.interfaces.Action](../../it.unibo.alchemist.model.interfaces/-action/index.html). This is inferred by the polarization vector contained in the cell.



## Parameters


jvm

| | |
|---|---|
| environment | the [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html) |
| node | the [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html) in which the [it.unibo.alchemist.model.interfaces.Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) is contained. This can be only a CellNode. |
| inPercent | a boolean parameter which set the way of expressing delta: if is true the cell movement will be (delta * cellDiameter), otherwise will be simply delta. If cellDiameter is zero, this [it.unibo.alchemist.model.interfaces.Action](../../it.unibo.alchemist.model.interfaces/-action/index.html) will in both cases behave like inPercent == false. |
| delta | the distance at which the cell will be moved. |




