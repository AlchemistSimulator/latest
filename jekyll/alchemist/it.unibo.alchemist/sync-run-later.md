---
title: syncRunLater
---
//[alchemist](../../index.html)/[it.unibo.alchemist](index.html)/[syncRunLater](sync-run-later.html)



# syncRunLater



[jvm]\
fun <[T](sync-run-later.html) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [syncRunLater](sync-run-later.html)(task: () -> [T](sync-run-later.html)): [T](sync-run-later.html)



Runs the given task on the FX thread and waits for the task to finish, returning any value the task returns. Throws an exception if the task takes more than a given amount of milliseconds.



## Parameters


jvm

| | |
|---|---|
| task | the task to execute. |




