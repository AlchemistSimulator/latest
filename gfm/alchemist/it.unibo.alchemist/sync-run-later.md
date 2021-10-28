//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[syncRunLater](sync-run-later.md)

# syncRunLater

[jvm]\
fun <[T](sync-run-later.md) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)> [syncRunLater](sync-run-later.md)(task: () -> [T](sync-run-later.md)): [T](sync-run-later.md)

Runs the given task on the FX thread and waits for the task to finish, returning any value the task returns. Throws an exception if the task takes more than a given amount of milliseconds.

## Parameters

jvm

| | |
|---|---|
| task | the task to execute. |
