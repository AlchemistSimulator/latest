---
title: PropertyFactory
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[PropertyFactory](index.html)



# PropertyFactory



[jvm]\
class [PropertyFactory](index.html)

Factory for custom {@code Property}.



## Functions


| Name | Summary |
|---|---|
| [getAWTColorChannelProperty](get-a-w-t-color-channel-property.html) | [jvm]<br>open fun [getAWTColorChannelProperty](get-a-w-t-color-channel-property.html)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [RangedIntegerProperty](../-ranged-integer-property/index.html)<br>open fun [getAWTColorChannelProperty](get-a-w-t-color-channel-property.html)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RangedIntegerProperty](../-ranged-integer-property/index.html)<br>Returns a new [RangedIntegerProperty](../-ranged-integer-property/index.html) with range between 255 and 0 and a name that identifies the color channel. |
| [getFXColorChannelProperty](get-f-x-color-channel-property.html) | [jvm]<br>open fun [getFXColorChannelProperty](get-f-x-color-channel-property.html)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [RangedDoubleProperty](../-ranged-double-property/index.html)<br>open fun [getFXColorChannelProperty](get-f-x-color-channel-property.html)(channel: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RangedDoubleProperty](../-ranged-double-property/index.html)<br>Returns a new [RangedDoubleProperty](../-ranged-double-property/index.html) with range between 1.0 and 0.0 and a name that identifies the color channel. |
| [getIncarnationsListProperty](get-incarnations-list-property.html) | [jvm]<br>open fun [getIncarnationsListProperty](get-incarnations-list-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): ListProperty<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>Returns a new ListProperty with all available incarnations of Alchemist found via reflection. |
| [getIncarnationsSetProperty](get-incarnations-set-property.html) | [jvm]<br>open fun [getIncarnationsSetProperty](get-incarnations-set-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): SetProperty<[String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)><br>Returns a new SetProperty with all available incarnations of Alchemist found via reflection. |
| [getPercentageRangedProperty](get-percentage-ranged-property.html) | [jvm]<br>open fun [getPercentageRangedProperty](get-percentage-ranged-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [RangedDoubleProperty](../-ranged-double-property/index.html)<br>open fun [getPercentageRangedProperty](get-percentage-ranged-property.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RangedDoubleProperty](../-ranged-double-property/index.html)<br>Returns a new [RangedDoubleProperty](../-ranged-double-property/index.html) with range between 100 and 0 and a name that identifies the {@code Property}. |

