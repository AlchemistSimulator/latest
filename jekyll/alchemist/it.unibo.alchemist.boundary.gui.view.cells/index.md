---
title: it.unibo.alchemist.boundary.gui.view.cells
---
//[alchemist](../../index.html)/[it.unibo.alchemist.boundary.gui.view.cells](index.html)



# Package it.unibo.alchemist.boundary.gui.view.cells



[jvm]\
This package contains all the cells needed for custom {@code ListViews}.



## Types


| Name | Summary |
|---|---|
| [AbstractEffectCell](-abstract-effect-cell/index.html) | [jvm]<br>abstract class [AbstractEffectCell](-abstract-effect-cell/index.html)<[T](-abstract-effect-cell/index.html)> : ListCell<T> <br>Abstract class that models a ListView Cell to represent [it.unibo.alchemist.boundary.gui.effects.EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)s or [it.unibo.alchemist.boundary.gui.effects.EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)s. |
| [EffectCell](-effect-cell/index.html) | [jvm]<br>open class [EffectCell](-effect-cell/index.html)<[P](-effect-cell/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> : [AbstractEffectCell](-abstract-effect-cell/index.html)<[EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)<[P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>> <br>This ListView cell implements the [AbstractEffectCell](-abstract-effect-cell/index.html) for containing an [EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html). |
| [EffectGroupCell](-effect-group-cell/index.html) | [jvm]<br>open class [EffectGroupCell](-effect-group-cell/index.html)<[P](-effect-group-cell/index.html) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> : [AbstractEffectCell](-abstract-effect-cell/index.html)<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html)<[P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>> <br>This ListView cell implements the [AbstractEffectCell](-abstract-effect-cell/index.html) for containing an [EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.html). |

