---
title: EffectPropertiesController
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.controller](../index.html)/[EffectPropertiesController](index.html)



# EffectPropertiesController



[jvm]\
open class [EffectPropertiesController](index.html) : Initializable

This class models a JavaFX controller for EffectProperties.fxml. 



 Using the FXML design it builds the basic components, then using reflection on the effect specified in [constructor](-effect-properties-controller.html) it builds up the other effect-specific controls.



## Constructors


| | |
|---|---|
| [EffectPropertiesController](-effect-properties-controller.html) | [jvm]<br>open fun [EffectPropertiesController](-effect-properties-controller.html)(effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html), stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [effectNameProperty](effect-name-property.html) | [jvm]<br>open fun [effectNameProperty](effect-name-property.html)(): StringProperty<br>The JavaFX Property that wraps the [effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.html)[name](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/get-name.html). |
| [initialize](initialize.html) | [jvm]<br>open fun [initialize](initialize.html)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |


## Properties


| Name | Summary |
|---|---|
| [EFFECT_PROPERTIES_LAYOUT](-e-f-f-e-c-t_-p-r-o-p-e-r-t-i-e-s_-l-a-y-o-u-t.html) | [jvm]<br>val [EFFECT_PROPERTIES_LAYOUT](-e-f-f-e-c-t_-p-r-o-p-e-r-t-i-e-s_-l-a-y-o-u-t.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |

