---
title: Exporter
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.loader.export](../index.html)/[Exporter](index.html)



# Exporter



[jvm]\
class [Exporter](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>?> : [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)> 

Writes on file data provided by a number of [Extractor](../-extractor/index.html)s. Produces a CSV with '#' as comment character. Even though this class implements [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html), it is not [java.io.Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).



## Parameters


jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type position type |



## Constructors


| | |
|---|---|
| [Exporter](-exporter.html) | [jvm]<br>open fun [Exporter](-exporter.html)(target: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), space: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), header: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), columns: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Extractor](../-extractor/index.html)>)<br>the target file |


## Functions


| Name | Summary |
|---|---|
| [finished](finished.html) | [jvm]<br>open fun [finished](finished.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [initialized](initialized.html) | [jvm]<br>open fun [initialized](initialized.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>) |
| [stepDone](step-done.html) | [jvm]<br>open fun [stepDone](step-done.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html), [P](../../it.unibo.alchemist.loader.shapes/-circle/index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](https://docs.oracle.com/javase/8/docs/api/java/lang/Iterable.html)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |

