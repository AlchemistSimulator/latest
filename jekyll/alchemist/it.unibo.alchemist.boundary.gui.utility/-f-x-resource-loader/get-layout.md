---
title: getLayout
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.utility](../index.html)/[FXResourceLoader](index.html)/[getLayout](get-layout.html)



# getLayout



[jvm]\
open fun <[T](get-layout.html) : Node?> [getLayout](get-layout.html)(controller: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)



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
open fun <[T](get-layout.html) : Node?> [getLayout](get-layout.html)(layoutName: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)): [T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)



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



