---
title: VerticalFlowLayout
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.layouts](../index.html)/[VerticalFlowLayout](index.html)



# VerticalFlowLayout



[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()



~~class~~ [~~VerticalFlowLayout~~](index.html) ~~:~~ [~~AFlowLayout~~](../-a-flow-layout/index.html)

A vertical layout manager similar to java.awt.FlowLayout. Like FlowLayout components do not expand to fill available space except when the horizontal alignment is BOTH in which case components are stretched horizontally. Unlike FlowLayout, components will not wrap to form another column if there isn't enough space vertically. VerticalLayout can optionally anchor components to the top or bottom of the display area or center them between the top and bottom. Revision date 12th July 2001 Homepage:www.kagi.com/equitysoft - Based on 'FlexLayout' in Java class libraries Vol 2 Chan/Lee Addison-Wesley 1998



## Constructors


| | |
|---|---|
| [VerticalFlowLayout](-vertical-flow-layout.html) | [jvm]<br>open fun [VerticalFlowLayout](-vertical-flow-layout.html)(ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Constructs an instance of VerticalLayout with a vertical vgap of 5 pixels, horizontal centering and anchored to the top of the display area. |
| [VerticalFlowLayout](-vertical-flow-layout.html) | [jvm]<br>open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Constructs a VerticalLayout instance with horizontal centering, anchored to the top with the specified vgap. |
| [VerticalFlowLayout](-vertical-flow-layout.html) | [jvm]<br>open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Constructs a VerticalLayout instance anchored to the top with the specified vgap and horizontal alignment. |
| [VerticalFlowLayout](-vertical-flow-layout.html) | [jvm]<br>open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), anchor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Constructs a VerticalLayout instance with the specified vgap, horizontal alignment and anchoring. |


## Functions


| Name | Summary |
|---|---|
| [addLayoutComponent](../-a-flow-layout/add-layout-component.html) | [jvm]<br>fun [addLayoutComponent](../-a-flow-layout/add-layout-component.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html))<br>abstract fun [addLayoutComponent](index.html#1607738721%2FFunctions%2F-134779887)(p: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), p1: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [getComponentOrder](../-a-flow-layout/get-component-order.html) | [jvm]<br>open fun [getComponentOrder](../-a-flow-layout/get-component-order.html)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the component you want to know the order |
| [getComponentsList](../-a-flow-layout/get-components-list.html) | [jvm]<br>open fun [getComponentsList](../-a-flow-layout/get-components-list.html)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)><br>a list with the ordered components |
| [isOrdered](../-a-flow-layout/is-ordered.html) | [jvm]<br>open fun [isOrdered](../-a-flow-layout/is-ordered.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the components are ordered |
| [layoutContainer](layout-container.html) | [jvm]<br>open fun [layoutContainer](layout-container.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html))<br>Lays out the container.<br>[jvm]<br>abstract fun [layoutContainer](index.html#1341255786%2FFunctions%2F-134779887)(p: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)) |
| [minimumLayoutSize](../-a-flow-layout/minimum-layout-size.html) | [jvm]<br>fun [minimumLayoutSize](../-a-flow-layout/minimum-layout-size.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html)<br>abstract fun [minimumLayoutSize](index.html#-151295896%2FFunctions%2F-134779887)(p: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [preferredLayoutSize](../-a-flow-layout/preferred-layout-size.html) | [jvm]<br>fun [preferredLayoutSize](../-a-flow-layout/preferred-layout-size.html)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html)<br>abstract fun [preferredLayoutSize](index.html#1593560981%2FFunctions%2F-134779887)(p: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [removeLayoutComponent](../-a-flow-layout/remove-layout-component.html) | [jvm]<br>fun [removeLayoutComponent](../-a-flow-layout/remove-layout-component.html)(comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html))<br>abstract fun [removeLayoutComponent](index.html#-327173290%2FFunctions%2F-134779887)(p: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [setComponentOrder](../-a-flow-layout/set-component-order.html) | [jvm]<br>fun [setComponentOrder](../-a-flow-layout/set-component-order.html)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html), order: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>the component you want to order |
| [toString](../-a-flow-layout/to-string.html) | [jvm]<br>open fun [toString](../-a-flow-layout/to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

