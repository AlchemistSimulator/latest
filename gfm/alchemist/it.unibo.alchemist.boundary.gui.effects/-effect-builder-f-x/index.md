//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectBuilderFX](index.md)

# EffectBuilderFX

[jvm]\
open class [EffectBuilderFX](index.md)

Class that lets the user choose the effect from all it can find.

## Constructors

| | |
|---|---|
| [EffectBuilderFX](-effect-builder-f-x.md) | [jvm]<br>open fun [EffectBuilderFX](-effect-builder-f-x.md)()<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [chooseAndLoad](choose-and-load.md) | [jvm]<br>open fun <[P](choose-and-load.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [chooseAndLoad](choose-and-load.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Asks the user to chose an effect and returns a new instance of the desired class. |
| [getFoundEffects](get-found-effects.md) | [jvm]<br>open fun [getFoundEffects](get-found-effects.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [EffectFX](../-effect-f-x/index.md)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>><br>Gets an unmodifiable view of the effects found during construction. |
| [getResult](get-result.md) | [jvm]<br>open fun <[P](get-result.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?, [C](get-result.md) : [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [getResult](get-result.md)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[C](get-result.md)>><br>Asks the user to chose an effect and returns the related Class. |
| [instantiateEffect](instantiate-effect.md) | [jvm]<br>open fun <[P](instantiate-effect.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>?> [instantiateEffect](instantiate-effect.md)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)>>): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-time-monitor/index.md)><br>Instantiates the desired effect. |
