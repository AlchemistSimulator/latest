//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.layouts](../index.md)/[AFlowLayout](index.md)

# AFlowLayout

[jvm]\
@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()

~~abstract~~ ~~class~~ [~~AFlowLayout~~](index.md) ~~:~~ [~~LayoutManager~~](https://docs.oracle.com/javase/8/docs/api/java/awt/LayoutManager.html)~~,~~ [~~Serializable~~](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)

## Constructors

| | |
|---|---|
| [AFlowLayout](-a-flow-layout.md) | [jvm]<br>open fun [AFlowLayout](-a-flow-layout.md)(hgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), anchor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>the vertical gap between components |

## Functions

| Name | Summary |
|---|---|
| [addLayoutComponent](add-layout-component.md) | [jvm]<br>fun [addLayoutComponent](add-layout-component.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [getComponentOrder](get-component-order.md) | [jvm]<br>open fun [getComponentOrder](get-component-order.md)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the component you want to know the order |
| [getComponentsList](get-components-list.md) | [jvm]<br>open fun [getComponentsList](get-components-list.md)(): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)><br>a list with the ordered components |
| [isOrdered](is-ordered.md) | [jvm]<br>open fun [isOrdered](is-ordered.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the components are ordered |
| [layoutContainer](layout-container.md) | [jvm]<br>abstract fun [layoutContainer](layout-container.md)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)) |
| [minimumLayoutSize](minimum-layout-size.md) | [jvm]<br>fun [minimumLayoutSize](minimum-layout-size.md)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [preferredLayoutSize](preferred-layout-size.md) | [jvm]<br>fun [preferredLayoutSize](preferred-layout-size.md)(parent: [Container](https://docs.oracle.com/javase/8/docs/api/java/awt/Container.html)): [Dimension](https://docs.oracle.com/javase/8/docs/api/java/awt/Dimension.html) |
| [removeLayoutComponent](remove-layout-component.md) | [jvm]<br>fun [removeLayoutComponent](remove-layout-component.md)(comp: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html)) |
| [setComponentOrder](set-component-order.md) | [jvm]<br>fun [setComponentOrder](set-component-order.md)(c: [Component](https://docs.oracle.com/javase/8/docs/api/java/awt/Component.html), order: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>the component you want to order |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

## Properties

| Name | Summary |
|---|---|
| [BOTH](-b-o-t-h.md) | [jvm]<br>val [BOTH](-b-o-t-h.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates stretching the component horizontally. |
| [CENTER](-c-e-n-t-e-r.md) | [jvm]<br>val [CENTER](-c-e-n-t-e-r.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates centering. |
| [LEFT](-l-e-f-t.md) | [jvm]<br>val [LEFT](-l-e-f-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates left justification. |
| [RIGHT](-r-i-g-h-t.md) | [jvm]<br>val [RIGHT](-r-i-g-h-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The horizontal alignment constant that designates right justification. |
| [TOP](-t-o-p.md) | [jvm]<br>val [TOP](-t-o-p.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The anchoring constant that designates anchoring to the top of the display area. |

## Inheritors

| Name |
|---|
| [HorizontalFlowLayout](../-horizontal-flow-layout/index.md) |
| [VerticalFlowLayout](../-vertical-flow-layout/index.md) |
