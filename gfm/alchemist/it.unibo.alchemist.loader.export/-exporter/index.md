//[alchemist](../../../index.md)/[it.unibo.alchemist.loader.export](../index.md)/[Exporter](index.md)

# Exporter

[jvm]\
class [Exporter](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>?> : [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md)<[T](../-mean-squared-error/index.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)> 

Writes on file data provided by a number of [Extractor](../-extractor/index.md)s. Produces a CSV with '#' as comment character. Even though this class implements [OutputMonitor](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.md), it is not [java.io.Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html).

## Parameters

jvm

| | |
|---|---|
| <T> | Concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md) type position type |

## Constructors

| | |
|---|---|
| [Exporter](-exporter.md) | [jvm]<br>open fun [Exporter](-exporter.md)(target: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), space: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), header: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html), columns: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Extractor](../-extractor/index.md)>)<br>the target file |

## Functions

| Name | Summary |
|---|---|
| [finished](finished.md) | [jvm]<br>open fun [finished](finished.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-mean-squared-error/index.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [initialized](initialized.md) | [jvm]<br>open fun [initialized](initialized.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-mean-squared-error/index.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>) |
| [stepDone](step-done.md) | [jvm]<br>open fun [stepDone](step-done.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../-mean-squared-error/index.md), [P](../../it.unibo.alchemist.loader.shapes/-rectangle/index.md)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.md)<[T](../-mean-squared-error/index.md)>, time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md), step: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
