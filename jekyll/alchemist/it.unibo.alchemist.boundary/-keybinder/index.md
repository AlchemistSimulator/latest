---
title: Keybinder
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary](../index.html)/[Keybinder](index.html)



# Keybinder



[jvm]\
class [Keybinder](index.html) : App

The keybinder app.



## Constructors


| | |
|---|---|
| [Keybinder](-keybinder.html) | [jvm]<br>fun [Keybinder](-keybinder.html)() |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [checkboxItem](index.html#1485722477%2FFunctions%2F-134779887) | [jvm]<br>fun [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).[checkboxItem](index.html#1485722477%2FFunctions%2F-134779887)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), state: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html) |
| [createPrimaryScene](index.html#-192477665%2FFunctions%2F-134779887) | [jvm]<br>open fun [createPrimaryScene](index.html#-192477665%2FFunctions%2F-134779887)(view: UIComponent): Scene |
| [fire](index.html#-2009960628%2FFunctions%2F-134779887) | [jvm]<br>fun <[T](index.html#-2009960628%2FFunctions%2F-134779887) : FXEvent> [fire](index.html#-2009960628%2FFunctions%2F-134779887)(event: [T](index.html#-2009960628%2FFunctions%2F-134779887)) |
| [getHostServices](index.html#792481849%2FFunctions%2F-134779887) | [jvm]<br>fun [getHostServices](index.html#792481849%2FFunctions%2F-134779887)(): HostServices |
| [getParameters](index.html#-807279243%2FFunctions%2F-134779887) | [jvm]<br>fun [getParameters](index.html#-807279243%2FFunctions%2F-134779887)(): Application.Parameters |
| [init](index.html#-1813461483%2FFunctions%2F-134779887) | [jvm]<br>open fun [init](index.html#-1813461483%2FFunctions%2F-134779887)() |
| [inject](index.html#-1396274593%2FFunctions%2F-134779887) | [jvm]<br>inline fun <[T](index.html#-1396274593%2FFunctions%2F-134779887) : Component, ScopedInstance> [inject](index.html#-1396274593%2FFunctions%2F-134779887)(scope: Scope): [ReadOnlyProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-only-property/index.html)<App, [T](index.html#-1396274593%2FFunctions%2F-134779887)> |
| [item](index.html#1984566858%2FFunctions%2F-134779887) | [jvm]<br>fun [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).[item](index.html#1984566858%2FFunctions%2F-134779887)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), shortcut: [MenuShortcut](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuShortcut.html)?, op: [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html) |
| [k](index.html#2002764807%2FFunctions%2F-134779887) | [jvm]<br>fun <[T](index.html#2002764807%2FFunctions%2F-134779887) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [k](index.html#2002764807%2FFunctions%2F-134779887)(javaClass: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](index.html#2002764807%2FFunctions%2F-134779887)>): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.html#2002764807%2FFunctions%2F-134779887)> |
| [loadConfig](index.html#150043495%2FFunctions%2F-134779887) | [jvm]<br>open fun [loadConfig](index.html#150043495%2FFunctions%2F-134779887)(): ConfigProperties |
| [menu](index.html#363687008%2FFunctions%2F-134779887) | [jvm]<br>fun [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).[menu](index.html#363687008%2FFunctions%2F-134779887)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), op: [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [notifyPreloader](index.html#-1908879305%2FFunctions%2F-134779887) | [jvm]<br>fun [notifyPreloader](index.html#-1908879305%2FFunctions%2F-134779887)(p0: Preloader.PreloaderNotification) |
| [onBeforeShow](index.html#-840480396%2FFunctions%2F-134779887) | [jvm]<br>open fun [onBeforeShow](index.html#-840480396%2FFunctions%2F-134779887)(view: UIComponent) |
| [setOnAction](index.html#-1109984550%2FFunctions%2F-134779887) | [jvm]<br>fun [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html).[setOnAction](index.html#-1109984550%2FFunctions%2F-134779887)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), action: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [setOnItem](index.html#-605087074%2FFunctions%2F-134779887) | [jvm]<br>fun [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html).[setOnItem](index.html#-605087074%2FFunctions%2F-134779887)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), action: (state: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [setOnMouseClicked](index.html#-1618459837%2FFunctions%2F-134779887) | [jvm]<br>fun [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).[setOnMouseClicked](index.html#-1618459837%2FFunctions%2F-134779887)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), button: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), clickCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), op: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [shouldShowPrimaryStage](index.html#-202216325%2FFunctions%2F-134779887) | [jvm]<br>open fun [shouldShowPrimaryStage](index.html#-202216325%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [start](index.html#2015417757%2FFunctions%2F-134779887) | [jvm]<br>open override fun [start](index.html#2015417757%2FFunctions%2F-134779887)(stage: Stage) |
| [stop](index.html#517658949%2FFunctions%2F-134779887) | [jvm]<br>open override fun [stop](index.html#517658949%2FFunctions%2F-134779887)() |
| [trayicon](index.html#684053850%2FFunctions%2F-134779887) | [jvm]<br>fun [trayicon](index.html#684053850%2FFunctions%2F-134779887)(image: [BufferedImage](https://docs.oracle.com/javase/8/docs/api/java/awt/image/BufferedImage.html), tooltip: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, implicitExit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), autoSize: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>fun [trayicon](index.html#-1364256247%2FFunctions%2F-134779887)(icon: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), tooltip: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, implicitExit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), autoSize: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [config](index.html#86612160%2FProperties%2F-134779887) | [jvm]<br>open override val [config](index.html#86612160%2FProperties%2F-134779887): ConfigProperties |
| [configBasePath](index.html#-184890422%2FProperties%2F-134779887) | [jvm]<br>open val [configBasePath](index.html#-184890422%2FProperties%2F-134779887): [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html) |
| [configCharset](index.html#-1266022994%2FProperties%2F-134779887) | [jvm]<br>open override val [configCharset](index.html#-1266022994%2FProperties%2F-134779887): [Charset](https://docs.oracle.com/javase/8/docs/api/java/nio/charset/Charset.html) |
| [configPath](index.html#1384246939%2FProperties%2F-134779887) | [jvm]<br>open override val [configPath](index.html#1384246939%2FProperties%2F-134779887): [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html) |
| [primaryView](index.html#-1303607567%2FProperties%2F-134779887) | [jvm]<br>open val [primaryView](index.html#-1303607567%2FProperties%2F-134779887): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out UIComponent> |
| [resources](index.html#-1865480941%2FProperties%2F-134779887) | [jvm]<br>val [resources](index.html#-1865480941%2FProperties%2F-134779887): ResourceLookup |
| [scope](index.html#234155332%2FProperties%2F-134779887) | [jvm]<br>open var [scope](index.html#234155332%2FProperties%2F-134779887): Scope |
| [workspace](index.html#250082467%2FProperties%2F-134779887) | [jvm]<br>val [workspace](index.html#250082467%2FProperties%2F-134779887): Workspace |

