//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.l10n](../index.md)/[LocalizedResourceBundle](index.md)/[get](get.md)

# get

[jvm]\
open fun [get](get.md)(): [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)

#### Return

a ResourceBundle using the current [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html) (if available), falling back to [US](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html#US--) in case no localized bundle is available.

[jvm]\
open fun [get](get.md)(resourceBundle: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [ResourceBundle](https://docs.oracle.com/javase/8/docs/api/java/util/ResourceBundle.html)

#### Return

a ResourceBundle using the current [Locale](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html) (if available), falling back to [US](https://docs.oracle.com/javase/8/docs/api/java/util/Locale.html#US--) in case no localized bundle is available.

## Parameters

jvm

| | |
|---|---|
| resourceBundle | the resource bundle to load (fully qualified name) |
