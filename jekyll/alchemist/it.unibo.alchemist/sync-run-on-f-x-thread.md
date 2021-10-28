---
title: syncRunOnFXThread
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[syncRunOnFXThread](sync-run-on-f-x-thread.html)



# syncRunOnFXThread



[jvm]\
fun <[T](sync-run-on-f-x-thread.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [syncRunOnFXThread](sync-run-on-f-x-thread.html)(task: () -> [T](sync-run-on-f-x-thread.html)): [T](sync-run-on-f-x-thread.html)



Checks if the current thread is the FX Application thread and calls [syncRunLater](sync-run-later.html) if so, otherwise runs the task.



## Parameters


jvm

| | |
|---|---|
| task | the task to execute. |




