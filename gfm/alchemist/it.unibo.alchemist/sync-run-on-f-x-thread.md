//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[syncRunOnFXThread](sync-run-on-f-x-thread.md)

# syncRunOnFXThread

[jvm]\
fun <[T](sync-run-on-f-x-thread.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [syncRunOnFXThread](sync-run-on-f-x-thread.md)(task: () -> [T](sync-run-on-f-x-thread.md)): [T](sync-run-on-f-x-thread.md)

Checks if the current thread is the FX Application thread and calls [syncRunLater](sync-run-later.md) if so, otherwise runs the task.

## Parameters

jvm

| | |
|---|---|
| task | the task to execute. |
