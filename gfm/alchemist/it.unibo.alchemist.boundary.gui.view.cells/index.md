//[alchemist](../../index.md)/[it.unibo.alchemist.boundary.gui.view.cells](index.md)

# Package it.unibo.alchemist.boundary.gui.view.cells

[jvm]\
This package contains all the cells needed for custom {@code ListViews}.

## Types

| Name | Summary |
|---|---|
| [AbstractEffectCell](-abstract-effect-cell/index.md) | [jvm]<br>abstract class [AbstractEffectCell](-abstract-effect-cell/index.md)<[T](-abstract-effect-cell/index.md)> : ListCell<[T](../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md)> <br>Abstract class that models a ListView Cell to represent [it.unibo.alchemist.boundary.gui.effects.EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)s or [it.unibo.alchemist.boundary.gui.effects.EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)s. |
| [EffectCell](-effect-cell/index.md) | [jvm]<br>open class [EffectCell](-effect-cell/index.md)<[P](-effect-cell/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>?> : [AbstractEffectCell](-abstract-effect-cell/index.md)<[EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)<[P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>> <br>This ListView cell implements the [AbstractEffectCell](-abstract-effect-cell/index.md) for containing an [EffectFX](../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md). |
| [EffectGroupCell](-effect-group-cell/index.md) | [jvm]<br>open class [EffectGroupCell](-effect-group-cell/index.md)<[P](-effect-group-cell/index.md) : [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>?> : [AbstractEffectCell](-abstract-effect-cell/index.md)<[EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md)<[P](../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>> <br>This ListView cell implements the [AbstractEffectCell](-abstract-effect-cell/index.md) for containing an [EffectGroup](../it.unibo.alchemist.boundary.gui.effects/-effect-group/index.md). |
