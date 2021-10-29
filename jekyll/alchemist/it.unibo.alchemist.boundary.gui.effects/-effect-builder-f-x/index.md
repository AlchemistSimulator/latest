---
title: EffectBuilderFX
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectBuilderFX](index.html)



# EffectBuilderFX



[jvm]\
open class [EffectBuilderFX](index.html)

Class that lets the user choose the effect from all it can find.



## Constructors


| | |
|---|---|
| [EffectBuilderFX](-effect-builder-f-x.html) | [jvm]<br>open fun [EffectBuilderFX](-effect-builder-f-x.html)()<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [chooseAndLoad](choose-and-load.html) | [jvm]<br>open fun <[P](choose-and-load.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> [chooseAndLoad](choose-and-load.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)><br>Asks the user to chose an effect and returns a new instance of the desired class. |
| [getFoundEffects](get-found-effects.html) | [jvm]<br>open fun [getFoundEffects](get-found-effects.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [EffectFX](../-effect-f-x/index.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>>><br>Gets an unmodifiable view of the effects found during construction. |
| [getResult](get-result.html) | [jvm]<br>open fun <[P](get-result.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?, [C](get-result.html) : [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> [getResult](get-result.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[C](get-result.html)>><br>Asks the user to chose an effect and returns the related Class. |
| [instantiateEffect](instantiate-effect.html) | [jvm]<br>open fun <[P](instantiate-effect.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>?> [instantiateEffect](instantiate-effect.html)(clazz: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<out [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)>>): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-serializer/effect-from-file.html)><br>Instantiates the desired effect. |

