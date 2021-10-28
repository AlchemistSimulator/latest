---
title: PropertyTypeAdapter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.view.properties](../index.html)/[PropertyTypeAdapter](index.html)



# PropertyTypeAdapter



[jvm]\
interface [PropertyTypeAdapter](index.html)<[T](index.html) : Property<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>?> : JsonSerializer<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> , JsonDeserializer<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> 

This interface lets implement classes for JavaFX custom property serialization.



## Parameters


jvm

| | |
|---|---|
| <T> | the Property type |



## Functions


| Name | Summary |
|---|---|
| [deserialize](deserialize.html) | [jvm]<br>abstract fun [deserialize](deserialize.html)(json: JsonElement, typeOfT: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonDeserializationContext): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html) |
| [serialize](serialize.html) | [jvm]<br>abstract fun [serialize](serialize.html)(src: [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), typeOfSrc: [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html), context: JsonSerializationContext): JsonElement |


## Properties


| Name | Summary |
|---|---|
| [BEAN](-b-e-a-n.html) | [jvm]<br>val [BEAN](-b-e-a-n.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "bean". |
| [NAME](-n-a-m-e.html) | [jvm]<br>val [NAME](-n-a-m-e.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "name". |
| [VALUE](-v-a-l-u-e.html) | [jvm]<br>val [VALUE](-v-a-l-u-e.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Static default JSON key for field "value". |

