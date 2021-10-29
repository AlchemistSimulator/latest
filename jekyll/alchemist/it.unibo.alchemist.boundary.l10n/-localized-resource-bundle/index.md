---
title: LocalizedResourceBundle
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.l10n](../index.html)/[LocalizedResourceBundle](index.html)



# LocalizedResourceBundle



[jvm]\
class [LocalizedResourceBundle](index.html)

Shorthand for getting resources.



## Functions


| Name | Summary |
|---|---|
| [get](get.html) | [jvm]<br>open fun [get](get.html)(): [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)<br>a ResourceBundle using the current [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html) (if available), falling back to [US](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html#US--) in case no localized bundle is available.<br>[jvm]<br>open fun [get](get.html)(resourceBundle: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)<br>the resource bundle to load (fully qualified name) |
| [getString](get-string.html) | [jvm]<br>open fun [getString](get-string.html)(key: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Looks up on the property files and returns the correct String. |

