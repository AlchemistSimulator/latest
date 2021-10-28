//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.controller](../index.md)/[EffectPropertiesController](index.md)

# EffectPropertiesController

[jvm]\
open class [EffectPropertiesController](index.md) : Initializable

This class models a JavaFX controller for EffectProperties.fxml. 

 Using the FXML design it builds the basic components, then using reflection on the effect specified in [constructor](-effect-properties-controller.md) it builds up the other effect-specific controls.

## Constructors

| | |
|---|---|
| [EffectPropertiesController](-effect-properties-controller.md) | [jvm]<br>open fun [EffectPropertiesController](-effect-properties-controller.md)(effect: [EffectFX](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md), stack: JFXDrawersStack, thisDrawer: JFXDrawer)<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [effectNameProperty](effect-name-property.md) | [jvm]<br>open fun [effectNameProperty](effect-name-property.md)(): StringProperty<br>The JavaFX Property that wraps the [effect](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/index.md)[name](../../it.unibo.alchemist.boundary.gui.effects/-effect-f-x/get-name.md). |
| [initialize](initialize.md) | [jvm]<br>open fun [initialize](initialize.md)(location: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html), resources: [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)) |

## Properties

| Name | Summary |
|---|---|
| [EFFECT_PROPERTIES_LAYOUT](-e-f-f-e-c-t_-p-r-o-p-e-r-t-i-e-s_-l-a-y-o-u-t.md) | [jvm]<br>val [EFFECT_PROPERTIES_LAYOUT](-e-f-f-e-c-t_-p-r-o-p-e-r-t-i-e-s_-l-a-y-o-u-t.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Layout path. |
