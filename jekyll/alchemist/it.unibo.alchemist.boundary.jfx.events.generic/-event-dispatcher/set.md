---
title: set
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[EventDispatcher](index.html)/[set](set.html)



# set



[jvm]\
abstract operator fun [set](set.html)(trigger: [T](index.html), job: ([E](index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))



Adds a job to be performed whenever an event triggers the dispatcher through the [listener](listener.html).



## Parameters


jvm

| | |
|---|---|
| trigger | the type of the job that needs to occur. |
| job | the job that will happen whenever the given job occurs. |




