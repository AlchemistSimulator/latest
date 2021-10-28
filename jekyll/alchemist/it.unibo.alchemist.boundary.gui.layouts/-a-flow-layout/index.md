---
title: AFlowLayout
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.layouts](../index.html)/[AFlowLayout](index.html)



# AFlowLayout



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~abstract~~ ~~class~~ [~~AFlowLayout~~](index.html) ~~:~~ [~~LayoutManager~~](https://docs.oracle.com/javase/8/docs/api/java/awt/LayoutManager.html)~~,~~ [~~Serializable~~](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)



## Constructors


| | |
|---|---|
| [AFlowLayout](-a-flow-layout.html) | [jvm]<br>open fun [AFlowLayout](-a-flow-layout.html)(hgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), anchor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the vertical gap between components |


## Functions


| Name | Summary |
|---|---|
| [addLayoutComponent](add-layout-component.html) | [jvm]<br>fun [addLayoutComponent](add-layout-component.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [getComponentOrder](get-component-order.html) | [jvm]<br>open fun [getComponentOrder](get-component-order.html)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the component you want to know the order |
| [getComponentsList](get-components-list.html) | [jvm]<br>open fun [getComponentsList](get-components-list.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)><br>a list with the ordered components |
| [isOrdered](is-ordered.html) | [jvm]<br>open fun [isOrdered](is-ordered.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the components are ordered |
| [layoutContainer](layout-container.html) | [jvm]<br>abstract fun [layoutContainer](layout-container.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)) |
| [minimumLayoutSize](minimum-layout-size.html) | [jvm]<br>fun [minimumLayoutSize](minimum-layout-size.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [preferredLayoutSize](preferred-layout-size.html) | [jvm]<br>fun [preferredLayoutSize](preferred-layout-size.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [removeLayoutComponent](remove-layout-component.html) | [jvm]<br>fun [removeLayoutComponent](remove-layout-component.html)(comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [setComponentOrder](set-component-order.html) | [jvm]<br>fun [setComponentOrder](set-component-order.html)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html), order: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>the component you want to order |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [BOTH](-b-o-t-h.html) | [jvm]<br>val [BOTH](-b-o-t-h.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates stretching the component horizontally. |
| [CENTER](-c-e-n-t-e-r.html) | [jvm]<br>val [CENTER](-c-e-n-t-e-r.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates centering. |
| [LEFT](-l-e-f-t.html) | [jvm]<br>val [LEFT](-l-e-f-t.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates left justification. |
| [RIGHT](-r-i-g-h-t.html) | [jvm]<br>val [RIGHT](-r-i-g-h-t.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates right justification. |
| [TOP](-t-o-p.html) | [jvm]<br>val [TOP](-t-o-p.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The anchoring constant that designates anchoring to the top of the display area. |


## Inheritors


| Name |
|---|
| [HorizontalFlowLayout](../-horizontal-flow-layout/index.html) |
| [VerticalFlowLayout](../-vertical-flow-layout/index.html) |

