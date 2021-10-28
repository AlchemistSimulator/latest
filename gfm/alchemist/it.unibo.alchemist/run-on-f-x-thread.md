//[alchemist](../../index.md)/[it.unibo.alchemist](index.md)/[runOnFXThread](run-on-f-x-thread.md)

# runOnFXThread

[jvm]\
fun [runOnFXThread](run-on-f-x-thread.md)(task: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Checks if the current thread is the FX Application thread and calls runLater if so, otherwise runs the task.

## Parameters

jvm

| | |
|---|---|
| task | the task to execute. |