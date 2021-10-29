---
title: FXResourceLoader
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.utility](../index.html)/[FXResourceLoader](index.html)



# FXResourceLoader



[jvm]\
class [FXResourceLoader](index.html)

Utility class for loading resources related to layout.



## Functions


| Name | Summary |
|---|---|
| [getColoredIcon](get-colored-icon.html) | [jvm]<br>open fun [getColoredIcon](get-colored-icon.html)(iconCode: IconCode, color: Color): IconNode<br>Loads an icon from Google Material Design Icons. |
| [getInjectionErrorMessage](get-injection-error-message.html) | [jvm]<br>open fun [getInjectionErrorMessage](get-injection-error-message.html)(nodeName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), layoutFileName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Returns the standard message for a problem in class injection from FXML. |
| [getLayout](get-layout.html) | [jvm]<br>open fun <[T](get-layout.html) : Node?> [getLayout](get-layout.html)(layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): T<br>open fun <[T](get-layout.html) : Node?> [getLayout](get-layout.html)(controller: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): T<br>Loads a layout FXML file returning the base pane defined by the layout. |
| [getStyle](get-style.html) | [jvm]<br>open fun [getStyle](get-style.html)(cssFileName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Returns the [java.net.URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html) to a CSS stylesheet of given name in string form. |
| [getWhiteIcon](get-white-icon.html) | [jvm]<br>open fun [getWhiteIcon](get-white-icon.html)(iconCode: IconCode): IconNode<br>Loads an icon from Google Material Design Icons filled in white. |

