//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.md)/[EventDispatcher](index.md)/[set](set.md)

# set

[jvm]\
abstract operator fun [set](set.md)(trigger: [T](index.md), job: ([E](index.md)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Adds a job to be performed whenever an event triggers the dispatcher through the [listener](listener.md).

## Parameters

jvm

| | |
|---|---|
| trigger | the type of the job that needs to occur. |
| job | the job that will happen whenever the given job occurs. |
