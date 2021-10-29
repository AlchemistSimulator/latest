---
title: set
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.jfx.events.generic](../index.html)/[PersistentEventDispatcher](index.html)/[set](set.html)



# set



[jvm]\
open operator override fun [set](set.html)(trigger: [T](index.html), job: ([E](index.html)) -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))



Adds a job to be performed whenever an event triggers the dispatcher through the [listener](index.html#-1989041411%2FProperties%2F-134779887).



## Parameters


jvm

| | |
|---|---|
| trigger | the type of the job that needs to occur. |
| job | the job that will happen whenever the given job occurs. |




