//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.utility](../index.md)/[FXResourceLoader](index.md)/[getLayout](get-layout.md)

# getLayout

[jvm]\
open fun <[T](get-layout.md) : Node?> [getLayout](get-layout.md)(controller: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)

Loads a layout FXML file returning the base pane defined by the layout.

#### Return

the pane defined by the layout

## Parameters

jvm

| | |
|---|---|
| <T> | the generic type of pane |
| controller | the controller to associate to that layout |
| layoutName | the name of the layout; it should be the file name without extension |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if it cannot load the file for some reason |

[jvm]\
open fun <[T](get-layout.md) : Node?> [getLayout](get-layout.md)(layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)

Loads a layout FXML file returning the base pane defined by the layout. It doesn't set any controller.

#### Return

the pane defined by the layout

## Parameters

jvm

| | |
|---|---|
| <T> | the generic type of pane |
| layoutName | the name of the layout; it should be the file name without extension |

#### Throws

| | |
|---|---|
| [java.io.IOException](https://docs.oracle.com/javase/8/docs/api/java/io/IOException.html) | if it cannot load the file for some reason |
