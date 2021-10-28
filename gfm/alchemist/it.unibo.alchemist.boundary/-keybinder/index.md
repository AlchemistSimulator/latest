//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary](../index.md)/[Keybinder](index.md)

# Keybinder

[jvm]\
class [Keybinder](index.md) : App

The keybinder app.

## Constructors

| | |
|---|---|
| [Keybinder](-keybinder.md) | [jvm]<br>fun [Keybinder](-keybinder.md)() |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [jvm]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [checkboxItem](index.md#1485722477%2FFunctions%2F-267951372) | [jvm]<br>fun [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).[checkboxItem](index.md#1485722477%2FFunctions%2F-267951372)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), state: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html) |
| [createPrimaryScene](index.md#-192477665%2FFunctions%2F-267951372) | [jvm]<br>open fun [createPrimaryScene](index.md#-192477665%2FFunctions%2F-267951372)(view: UIComponent): Scene |
| [fire](index.md#-2009960628%2FFunctions%2F-267951372) | [jvm]<br>fun <[T](index.md#-2009960628%2FFunctions%2F-267951372) : FXEvent> [fire](index.md#-2009960628%2FFunctions%2F-267951372)(event: [T](index.md#-2009960628%2FFunctions%2F-267951372)) |
| [getHostServices](index.md#792481849%2FFunctions%2F-267951372) | [jvm]<br>fun [getHostServices](index.md#792481849%2FFunctions%2F-267951372)(): HostServices |
| [getParameters](index.md#-807279243%2FFunctions%2F-267951372) | [jvm]<br>fun [getParameters](index.md#-807279243%2FFunctions%2F-267951372)(): Application.Parameters |
| [init](index.md#-1813461483%2FFunctions%2F-267951372) | [jvm]<br>open fun [init](index.md#-1813461483%2FFunctions%2F-267951372)() |
| [inject](index.md#-1396274593%2FFunctions%2F-267951372) | [jvm]<br>inline fun <[T](index.md#-1396274593%2FFunctions%2F-267951372) : Component, ScopedInstance> [inject](index.md#-1396274593%2FFunctions%2F-267951372)(scope: Scope): [ReadOnlyProperty](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-only-property/index.html)<App, [T](index.md#-1396274593%2FFunctions%2F-267951372)> |
| [item](index.md#1984566858%2FFunctions%2F-267951372) | [jvm]<br>fun [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).[item](index.md#1984566858%2FFunctions%2F-267951372)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), shortcut: [MenuShortcut](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuShortcut.html)?, op: [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html) |
| [k](index.md#2002764807%2FFunctions%2F-267951372) | [jvm]<br>fun <[T](index.md#2002764807%2FFunctions%2F-267951372) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [k](index.md#2002764807%2FFunctions%2F-267951372)(javaClass: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[T](index.md#2002764807%2FFunctions%2F-267951372)>): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<[T](index.md#2002764807%2FFunctions%2F-267951372)> |
| [loadConfig](index.md#150043495%2FFunctions%2F-267951372) | [jvm]<br>open fun [loadConfig](index.md#150043495%2FFunctions%2F-267951372)(): ConfigProperties |
| [menu](index.md#363687008%2FFunctions%2F-267951372) | [jvm]<br>fun [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).[menu](index.md#363687008%2FFunctions%2F-267951372)(label: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), op: [PopupMenu](https://docs.oracle.com/javase/8/docs/api/java/awt/PopupMenu.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [notifyPreloader](index.md#-1908879305%2FFunctions%2F-267951372) | [jvm]<br>fun [notifyPreloader](index.md#-1908879305%2FFunctions%2F-267951372)(p0: Preloader.PreloaderNotification) |
| [onBeforeShow](index.md#-840480396%2FFunctions%2F-267951372) | [jvm]<br>open fun [onBeforeShow](index.md#-840480396%2FFunctions%2F-267951372)(view: UIComponent) |
| [setOnAction](index.md#-1109984550%2FFunctions%2F-267951372) | [jvm]<br>fun [MenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/MenuItem.html).[setOnAction](index.md#-1109984550%2FFunctions%2F-267951372)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), action: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [setOnItem](index.md#-605087074%2FFunctions%2F-267951372) | [jvm]<br>fun [CheckboxMenuItem](https://docs.oracle.com/javase/8/docs/api/java/awt/CheckboxMenuItem.html).[setOnItem](index.md#-605087074%2FFunctions%2F-267951372)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), action: (state: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [setOnMouseClicked](index.md#-1618459837%2FFunctions%2F-267951372) | [jvm]<br>fun [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).[setOnMouseClicked](index.md#-1618459837%2FFunctions%2F-267951372)(fxThread: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), button: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), clickCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), op: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [shouldShowPrimaryStage](index.md#-202216325%2FFunctions%2F-267951372) | [jvm]<br>open fun [shouldShowPrimaryStage](index.md#-202216325%2FFunctions%2F-267951372)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [start](index.md#2015417757%2FFunctions%2F-267951372) | [jvm]<br>open override fun [start](index.md#2015417757%2FFunctions%2F-267951372)(stage: Stage) |
| [stop](index.md#517658949%2FFunctions%2F-267951372) | [jvm]<br>open override fun [stop](index.md#517658949%2FFunctions%2F-267951372)() |
| [trayicon](index.md#684053850%2FFunctions%2F-267951372) | [jvm]<br>fun [trayicon](index.md#684053850%2FFunctions%2F-267951372)(image: [BufferedImage](https://docs.oracle.com/javase/8/docs/api/java/awt/image/BufferedImage.html), tooltip: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, implicitExit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), autoSize: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>fun [trayicon](index.md#-1364256247%2FFunctions%2F-267951372)(icon: [InputStream](https://docs.oracle.com/javase/8/docs/api/java/io/InputStream.html), tooltip: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, implicitExit: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), autoSize: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), op: [TrayIcon](https://docs.oracle.com/javase/8/docs/api/java/awt/TrayIcon.html).() -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [config](index.md#86612160%2FProperties%2F-267951372) | [jvm]<br>open override val [config](index.md#86612160%2FProperties%2F-267951372): ConfigProperties |
| [configBasePath](index.md#-184890422%2FProperties%2F-267951372) | [jvm]<br>open val [configBasePath](index.md#-184890422%2FProperties%2F-267951372): [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html) |
| [configCharset](index.md#-1266022994%2FProperties%2F-267951372) | [jvm]<br>open override val [configCharset](index.md#-1266022994%2FProperties%2F-267951372): [Charset](https://docs.oracle.com/javase/8/docs/api/java/nio/charset/Charset.html) |
| [configPath](index.md#1384246939%2FProperties%2F-267951372) | [jvm]<br>open override val [configPath](index.md#1384246939%2FProperties%2F-267951372): [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html) |
| [primaryView](index.md#-1303607567%2FProperties%2F-267951372) | [jvm]<br>open val [primaryView](index.md#-1303607567%2FProperties%2F-267951372): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)<out UIComponent> |
| [resources](index.md#-1865480941%2FProperties%2F-267951372) | [jvm]<br>val [resources](index.md#-1865480941%2FProperties%2F-267951372): ResourceLookup |
| [scope](index.md#234155332%2FProperties%2F-267951372) | [jvm]<br>open var [scope](index.md#234155332%2FProperties%2F-267951372): Scope |
| [workspace](index.md#250082467%2FProperties%2F-267951372) | [jvm]<br>val [workspace](index.md#250082467%2FProperties%2F-267951372): Workspace |
